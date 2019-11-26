# Dataset for image segmentation

This dataset was created by using the [Carla Simulator](https://github.com/carla-simulator/carla) simulator. 
If you are interested in creating your own image segmentation dataset using carla you can find full documentation and the code I used on my [GitHub page](https://github.com/cpow-89/carla_image_segmentation).

### Image Example

[image1]: https://github.com/cpow-89/carla_image_segmentation_dataset/blob/master/doc_images/example.png "Example image"
![Example image][image1]


### Segmentation Mask Example

[image2]: https://github.com/cpow-89/carla_image_segmentation_dataset/blob/master/doc_images/example_mask.png "Example label"
![Example label][image2]



# Dataset Description:

This dataset has been created on windows using carla simulator v.0.9.5. The dataset contains 2206 images + image segmentation masks with a resolution of 800x600 pixels. The dataset also provides a valid.txt file which includes information on which files to use for validation. If you are interested in an example on how to use this dataset to train an UNet Model take a look at my [GitHub page](https://github.com/cpow-89/carla_image_segmentation).

### How to interpret the codes of the image segmentation mask?

The codes are identical to the offical carla coding.


| Code          | Label         |
| ------------- |:-------------:| 
| 0             | Unlabeled     |
| 1             | Building      | 
| 2             | Fence         | 
| 3             | Other         | 
| 4             | Pedestrian    | 
| 5             | Pole          | 
| 6             | Road line     | 
| 7             | Road          | 
| 8             | Sidewalk      | 
| 9             | Vegetation    | 
| 10            | Car           | 
| 11            | Wall          | 
| 12            | Traffic sign  | 

### Limitations

The windows version of carla simulator v.0.9.5 does not include pedestrians. That´s why the dataset also does not include pedestrians.
