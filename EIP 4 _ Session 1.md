# EIP 4 | Session 1

### 1. Convolution
Convolution is training a model to detect a image of an object by detecting edges & gradient, texture & pattern, part of object, combination of part of object form object. Methods are involved decting images i.e forward and back propogation.

### 2. Filters/Kernels
The filter are used to detect the basic feature of the model e.g vertical edge, horizontal edge, and textures and loudes feature of image can be detected with any background. It can be one dimension or multi dimension and size of filter varies. The output of channels is decided according to number of filters it applied. 

### 3. Epochs
One epoch means passing one full training network i.e backward and forward propogation one time.

### 4. 1x1 Convolution
When we are applying 1x1 convolution to  6x6x1 channel and 1x1x1 filter the what we will get output is same as input. When we apply 1x1 convolution to  6x6x512 channel and 1x1x512x32 filter output is 6x6x32 to reduce the number of channel in z-axis. 

### 5. 3x3 Convolution
3x3 Convolution is used as feature extractor in the image to extract particular type of edge or texture of the image. 3x3 filters multiply with the image pick out the same feature but increase the value.

### 6. Feature Maps
Feature Maps is the basically the output of the activations layer where the filter is applied.
### 7. Activation Function
Activation function is basically the weighted sum with the input adding the bias then neuron decide it should be fired or not. e.g their some activation fuction which allow values to pass its one or exculde it other values.

### 8. Receptive Field
Receptive Field is the space from where the input values are looked at. There are multiple layer then there is two type of receptive field gobal and local. 
a. Local receptive field is area from where one layer ahead input space is look at. 
b. Gobal receptive field is effected by layer the input layer you are looking at as well as original image size.


