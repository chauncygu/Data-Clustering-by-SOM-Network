%%%%%%%采用SOM网络进行聚类
clear all
load simplecluster_dataset;
[x,t]=simplecluster_dataset;
plot(x(1,:),x(2,:),'+');
dimension1=10;
dimension2=10;
net=selforgmap([dimension1,dimension2]);
view(net);
net=train(net,x);  
y=net(x);
classes=vec2ind(y);
