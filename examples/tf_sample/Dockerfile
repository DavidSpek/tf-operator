FROM  tensorflow/tensorflow:2.4.1
RUN pip install retrying
RUN mkdir -p /opt/kubeflow
COPY tf_smoke.py /opt/kubeflow/
ENTRYPOINT ["python", "/opt/kubeflow/tf_smoke.py"]
