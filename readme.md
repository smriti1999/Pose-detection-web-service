# Assignment 1 – FIT5225  
**Creating and Deploying an Image Object Detection Web Service within a Containerised Environment in Clouds**

## Student Details
- **Name**: Smriti Singh  
- **Student ID**: 34274227  
- **Tutor**: Jay Zhao

---

## 🎥 Video Demonstration  
A full 8-minute walkthrough of the architecture, Docker container, Kubernetes setup, and Locust testing. 


**Watch here**:  
https://drive.google.com/file/d/1za5oF3YiHj1KfvKNz1o7zExNUEN48jwa/view?usp=sharing 



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
