FROM python:3.12.11
RUN pip install gcsfs
RUN pip install pandas
COPY ./visualize.py .
CMD ["python", 'visualize.py']