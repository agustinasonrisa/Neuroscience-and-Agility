# Neuroscience-and-Agility
Neuroscience insights
import pandas as pd  
import matplotlib.pyplot as plt  

data = {'Sprint': [1, 2, 3], 'Completed_Tasks': [15, 20, 25]}  
df = pd.DataFrame(data)  

plt.plot(df['Sprint'], df['Completed_Tasks'])  
plt.title('Team Productivity Over Sprints')  
plt.show()  
