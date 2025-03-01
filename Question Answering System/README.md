# Question and answering system


!pip install streamlit

!npm install localtunnel

!pip install streamlit-webrtc


%%writefile app.py


!curl ipv4.icanhazip.com

# LocalTunnel asks for the password which is the IP of this machine. 

!streamlit run app.py &>./logs.txt & npx localtunnel --port 8501

!cat logs.txt   # For looking into the logs if there are any troubles.
