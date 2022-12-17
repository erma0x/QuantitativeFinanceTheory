#finanza 
## creazione trading automatico

### workflow
-   **I: Connecting to a Brokerage House**
-   **II: Trading System Development**
-   **III: Trading Model Development**
-   **IV:  Trading Model Deployment**
-   **V: Cloud Deployment**



## AI trading system in python
medium link: https://medium.com/swlh/build-an-ai-stock-trading-bot-for-free-4a46bec2a18

``` python
class TradingSystem(abc.ABC):

	def __init__(self, api, symbol, time_frame, system_id, system_label):
	self.api = api
	self.symbol = symbol
	self.time_frame = time_frame
	self.system_id = system_id
	self.system_label = system_label
	thread = threading.Thread(target=self.system_loop)
	thread.start()


	@abc.abstractmethod
	def place_buy_order(self):
	pass
	
	@abc.abstractmethod
	def place_sell_order(self):
	pass
	
	@abc.abstractmethod
	def system_loop(self):
	pass
```

``` python
# AI Portfolio Manager
class PortfolioManagementModel:

	def __init__(self):
		# Data in to test that the 
		# saving of weights worked
		data = pd.read_csv('IBM.csv')
		X = data['Delta Close']
		y = data.drop(['Delta Close'], axis=1)
		# Read structure from json
		json_file = open('model.json', 'r')
		json = json_file.read()
		json_file.close()
		self.network = model_from_json(json)
		# Read weights from HDF5
		self.network.load_weights("weights.h5")
		# Verify weights and structure are loaded
		y_pred = self.network.predict(X.values)
		y_pred = np.around(y_pred, 0)
		print(classification_report(y, y_pred))
	
	@abc.abstractmethod
	def place_buy_order(self):
	pass
	
	@abc.abstractmethod
	def place_sell_order(self):
	pass
	
	@abc.abstractmethod
	def system_loop(self):
	pass
	
PortfolioManagementModel()
```

#### oggetti per il trading algoritmico
- (function) datastream websocket

- (database) database securities master
	- securities historical datasets
	- test websocket quality

- (function) signal creation algorithm

- (function) optimal sizing algorithm
- (function) optimal operation capital
- (function) optimal laverage sizing 

- (function) entry positining algorithm

- (script) monitoring from remote in live 
	- performance stats
	- real operation and positions

- (server) trading server
