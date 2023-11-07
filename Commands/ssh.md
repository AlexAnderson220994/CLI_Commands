# SSH Commands

## Making an SSH key

- Create SSH key
````
ssh-keygen -t rsa -b 4096 -C youremailhere.com
````
- Showing the SSH key
````
cat <keyname>
````
- Assign permissions
````
chmod 400 <keyname>
````
OR
````
chmod +x <keyname>
````

## SSH Connection - GitBash

- Creating SSH agent PID
````
eval ssh-agent
````
OR
````
eval $(ssh-agent -s)
````
- Add SSH key
````
ssh-add ~/.ssh/keyname
````