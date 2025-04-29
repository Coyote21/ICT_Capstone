FROM python:latest

# Set the working directory inside the container
WORKDIR /app

# Copy the requirements file and install dependencies
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy the rest of the application files into the container
COPY . .

# Start the Question Answer Interface
CMD ["streamlit", "run", "/app/qa_interface.py"]
