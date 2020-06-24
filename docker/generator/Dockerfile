# Use an official Python runtime as a parent image
FROM python:3.6

# Set the working directory to /app
WORKDIR /app

# Install any needed packages specified in requirements.txt
ADD ./requirements.txt ./
RUN pip install --trusted-host pypi.python.org -r requirements.txt
ADD ./ ./

CMD ["python3", "app.py"]



