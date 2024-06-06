# Use Python 3.6 or later as a base image

# Copy contents into image
 
# Install pip dependencies from requirements

# Set YOUR_NAME environment variable

# Expose the correct port

# Create an entrypoint
FROM python:latest 
COPY . .
RUN pip install -r requirements.txt
ENV YOUR_NAME Ula
EXPOSE 5500
ENTRYpoint ["python", "app.py"]
