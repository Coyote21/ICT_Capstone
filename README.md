# ICT Capstone53 QA Interface  
## Clone the repo  
`git clone https://github.com/Coyote21/ICT_Capstone.git`  
## Build the Docker Image  
```bash
cd ICT_Capstone
docker build -t ict-capstone53 .
```  
## Run the App  
`docker run -p 8501:8501 ict-capstone53`  
or  
`docker run -d -p 8501:8501 ict-capstone53`  
if you want to detach after starting the container.  

Then open http://localhost:8501 in your browser.  
