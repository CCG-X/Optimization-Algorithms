# Optimization-Algorithms
Data set description


For the given dataset, there are 698 images of a face in different poses, the faces are 64x64 grayscale images.Each image have different orientation(poses),basically, the poses can be characterised as elevation and azimuth(image rotating left or right)
Here, 2 optimization algorithms are used to adjust the parameters until make the random initialized face images maps onto the real face poses.
The loss function here is defined as L(θ)=∥f(x;θ)−y∥, every input vector  x  must have a corresponding matched expected output  y , and we need a function  f  that depends on  x  and  θ .We measure the difference between a predicted output  f(x;θ) and a real, expected output  y , and try and minimise that difference by choosing a good setting for θ .
