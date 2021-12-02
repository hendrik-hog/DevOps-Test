FROM python:3.9
EXPOSE 8501
WORKDIR /app
RUN pip3 install --upgrade pip
RUN pip3 install setuptools wheel
COPY . .
RUN pip3 install -r requirements.txt
CMD streamlit run app.py