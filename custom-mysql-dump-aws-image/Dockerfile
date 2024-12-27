FROM bitnami/mysql:5.7

# Temporarily switch to root user
USER root

# Create mysql user
RUN useradd -r -u 1001 -m mysql

# Install AWS CLI
RUN apt-get update && apt-get install -y awscli && apt-get clean

# Switch back to MySQL user
USER mysql


