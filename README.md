# extract_ws
This repository is used to extract information and images from my ROS bag files.

## How to run these python code

I provided two python files here, both of them can extract images.

`bag2img_pose` file can extract 2d pose massages from ROS topic `/pose_estimate/str`

commands example:
```
python bag2img_pose test_2d_pose.bag

```

or
```
python bag2img test_2d_pose.bag

```
