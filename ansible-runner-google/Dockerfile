FROM ansible/ansible-runner:1.4.6

RUN pip3 install --no-cache google-auth==1.22.1 requests==2.22.0

CMD ["ansible-runner", "run", "/runner"]
