# ATM-Cash-Management
ATM cash prediction is one of the key issues for the bank. The available data in the bank is the cash withdrawal transactions that customers perform, and its amounts can vary greatly depending on various historical events. In this research, I tried to predict the behavior of one of these ATMs using the LSTM network and achieve high accuracy in this regard.
Among the most important effort in this regard were:
a) Obtaining, cleaning, and preprocessing daily customer withdrawal data and calculating the sum of these amounts per day.
b) In order to uniformize the data, withdrawal amounts with a large difference compared to their surrounding data (local minimum data) were removed, and their values were added to the next day value.
c) Omitted values on the unimportant dates were interpolated with their previous and next values and replaced.
d) A multilayer network was defined with two LSTM layers, two dense layers, and two dropout layers and applying adam optimizer. This definition was optimally characterized by several stages of review and investigation .
e) Network parameters were tuned over time by several estimates and examinations.
f) Favorable accuracy was obtained.
g) The results were analyzed and the error values were compared with the maximum acceptable loss for the bank.
