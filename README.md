# docker-react-template

```bash
rm -rf .git;
docker-compose build;
docker-compose run client create-react-app hello-world;
sudo chown -R $USER:$USER hello-world;
mv hello-world/* .;
mv hello-world/.gitignore .;
rm -rf hello-world;
```
