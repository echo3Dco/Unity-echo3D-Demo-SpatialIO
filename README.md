# Unity-echo3D-Demo-SpatialIO
Import an external 3D asset into a Spatial.io project in Unity from the echo3D cloud.

## Setup
* Built with [Unity 2021.3.21](https://unity3d.com/get-unity/download/archive) (Note: The echo3D Unity SDK requires 2020.3.25+ and Spatial.io requires Unity 2021.3.8+).
* [Register](https://www.echo3d.com/signup?utm_term={keyword}&utm_campaign=weapons_tutorial&utm_source=medium&utm_medium=blog) for FREE at echo3D.
* Clone this repo to view the sample project. The SDK has already been installed. Just upload the models to the echo3D console and add the API key and entry IDs (see below).

## Steps
* [Upload](https://docs.echo3d.co/quickstart/add-a-3d-model) the 'LoungeChair' model from the Models folder in the Unity project to the echo3D console.
* [Upon your first use](https://docs.spatial.io/), Spatial.io will prompt you to authenticate your account in Unity. You can also do this by clicking Unity menu > Spatial SDK > Account. Follow the instructions.
![spatialaccount](https://github.com/echo3Dco/Unity-echo3D-Demo-SpatialIO/assets/99516371/5d0c96df-5eec-4e62-bd10-09677f0349e9)
* Open the 'Environment' scene in Unity found at 'Assets/Examples/Space_SpatialIsland/Scenes/Environment.unity'.
* Select the 'echo3DHologram' object in the Hierarchy and add the [API key and entry ID](https://docs.echo3d.co/quickstart/access-the-console) in the Inspector.
![APIKeyandEntryId](https://github.com/echo3Dco/Unity-echo3D-Demo-SpatialIO/assets/99516371/cd080d83-68af-4734-a7e3-307a961707b2)
![apikey](https://github.com/echo3Dco/Unity-echo3D-Demo-SpatialIO/assets/99516371/7e27d007-7d10-4768-ad6c-7bc9d58ad567)
* In the echo3D console, click on the 'LoungeChair' content card and click on '[Metadata](https://docs.echo3d.com/unity/transforming-content)'.
* Add 'yAngle' with value 150.
* Add 'scale' with value .8.
  ![LoungeChairMetadata](https://github.com/echo3Dco/Unity-echo3D-Demo-SpatialIO/assets/99516371/fa0df874-69eb-4c16-8ff5-06282eb79f00)


## Run
Click Play in Unity to watch the chair appear.

## Learn More
Refer to our [documentation](https://docs.echo3d.com/) or [Youtube channel](https://www.youtube.com/@echo3Dco) to learn more.
Refer to [Spatial.io](https://www.spatial.io/) docs to learn more.

## Support
Feel free to reach out at [support@echo3D.com](mailto:support@echo3D.com) or join our [support channel](https://go.echo3d.co/join) on Slack.

## Troubleshooting
Visit our troubleshooting guide [here](https://docs.echo3d.com/unity/troubleshooting).

## Screenshots
![a](https://github.com/echo3Dco/Unity-echo3D-Demo-SpatialIO/assets/99516371/4894ad57-3085-4a18-8366-b2d1adbec832) <br>
![b](https://github.com/echo3Dco/Unity-echo3D-Demo-SpatialIO/assets/99516371/4a33a6cd-3cdf-470f-be7f-0cdd9c284a45)
