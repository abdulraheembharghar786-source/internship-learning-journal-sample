# 🧪 Hands-On Skills Gained (Detailed)

This section describes the practical skills developed while learning API workflow, server creation, request handling, and local testing.

---

## 1. Understanding API Workflow

Learned the complete lifecycle of an API-based application:

1. **Design** → Define what the API should do  
2. **Build** → Implement endpoints and logic  
3. **Test** → Verify responses and behavior  
4. **Debug** → Fix errors and improve reliability  
5. **Deploy** → Make the API accessible to users  

### Key Understanding
- Client → Server communication model  
- APIs act as a bridge between frontend, backend, and data systems  
- Real-world backend architecture and request–response cycle  

---

## 2. Creating a Simple Server

Built a basic local server using Python.

### Learned
- Server listens on a specific **port** (e.g., `localhost:8000`)  
- Waits for incoming client requests  
- Sends responses back to the client  

### Core Concepts
- **Host:** `localhost`  
- **Port:** `8000`  
- **Runtime:** Server runs continuously until stopped  

Practiced starting and stopping a local development server.

---

## 3. Handling HTTP Requests

Learned how servers process client requests using HTTP methods.

### HTTP Methods
- **GET** → Retrieve data from server  
- **POST** → Send new data to server  
- **PUT** → Update existing data  
- **DELETE** → Remove data  

### Learned to Handle
- URL path  
- Query parameters  
- Headers  
- Body data  

Practiced routing (mapping URL → function) and dynamic request processing.

---

## 4. Returning JSON Responses

Understood why **JSON (JavaScript Object Notation)** is used in APIs:
- Lightweight  
- Easy to read  
- Standard format for APIs  

### Example JSON Response

```json
{
  "status": "success",
  "message": "API is running"
}
