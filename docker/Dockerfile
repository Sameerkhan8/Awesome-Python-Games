# Use a lightweight Python image
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the entire repository to the container
COPY . /app

# Install necessary dependencies (add any specific dependencies you need)
RUN pip install -r requirements.txt

# Expose port 80
EXPOSE 80

# Run the application (replace with your application's entry point)
CMD ["python", "your_main_script.py"]

