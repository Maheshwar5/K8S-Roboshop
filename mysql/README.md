# For secrets, we're encrypting in base64 format. 
# Username:
$ echo -n shipping | base64
c2hpcHBpbmc=

# Password:
$ echo -n secret | base64
c2VjcmV0

# By defualt kubernetes will decode while pushing to Pod.