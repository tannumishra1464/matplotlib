# Matplotlib using python.
# Basic Charting Using Matplotlib.
%matplotlib in line
from matplotlib import pyplot as plt
plt.plot([1,2,3], [2,5,7])
plt.title('Tannus Data')
plt.ylabel('Y axia Data')
plt.show()
plt.plot([1,2,3], [2,5,7])
plt.title('Tannus Data')
plt.xlabel('This is "X" axis')
plt.ylabel('This is "Y" axis')
plt.show()

# Using Pyplot
from matplotlib import pyplot as plt
from matplotlib import style
style.use("ggplot")
x=[1,5,4]
y=[23,45,67]
x2=[3,7,3]
y2=[5,8,8]
plt.scatter(x,y, label='first')
plt.scatter(x2,y2, label='second')
plt.legend()
plt.show()
