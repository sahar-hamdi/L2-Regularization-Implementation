# L2-Regularization-Implementation
x1 = np.zeros((67, 3)) 
x1[:, 0]=np.arange(-1,1,0.03) 
print(x1.shape) 
y1=x1[:, 0]*3+x1[:, 0]*2 
print(x1[:5]) 
print(y1[:5]) 
plt.scatter(x1[:, 0],y1) 
x1[:, 1]=x1[:, 0]**2 
x1[:, 2]=x1[:, 0]**3 
print(x1.shape) 
print(y1.shape)

implement L2-Regularization with Gradinet Descent on this data.
