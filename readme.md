# Objective:  
**Creating and Deploying an Image Object Detection Web Service within a Containerised Environment in Clouds**

Details

The deployed FastAPI endpoints for human pose estimation:

- **Keypoint JSON Output**  
  [`/api/pose`](http://<your_public_ip>:30080/api/pose)  
  Example: `http://158.179.21.64:30080/api/pose`

- **Annotated Image Output**  
  [`/api/pose/image`](http://<your_public_ip>:30080/api/pose/image)  
  Example: `http://158.179.21.64:30080/api/pose/image`

You can test these endpoints using a POST request with a JSON payload like:

```json
{
  "id": "your-uuid-here",
  "image": "base64-encoded-jpeg-image"
}

