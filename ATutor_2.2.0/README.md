# Install
1. bring the containers up
```bash
docker-compose up -d
```
  
2. Navigate to http://localhost in a web browser and proceed to install
  
3. At the datbase setup step, select 'db' instead of localhost. User is root, and password is listed in the compose file
  
4. When the setup asks for a directory for media storage, select /var/tmp.

5. Ready to go.
  
6. To erase the machine and restore to default:
```bash
docker-compose down -v
```