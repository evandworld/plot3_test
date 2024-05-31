# plot3_test
MATLAB的plot3使用技巧
MATLAB的plot3使用技巧
% 设置xyz的值
x = [1,2,3,4,5];
y = [2,1,2,1,4];
z = [1,2,3,4,5];
默认绘图
figure;
plot3(x,y,z);
title('默认绘图');
45°视角绘图
figure;
plot3(x,y,z);
view(45,45);
title('45°视角绘图');
添加坐标轴的默认绘图：
figure;
plot3(x,y,z);
xlabel('X');ylabel('Y');zlabel('Z');
title('添加坐标轴的默认绘图');
自定义视角绘图：
figure;
plot3(x,y,z);
view(-23,30); %这里的-23,30为旋转视图时，左下角的值
% -23为方向角，30为仰角，单位为°
title('自定义视角绘图');




