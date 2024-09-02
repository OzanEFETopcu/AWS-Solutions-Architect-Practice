
# Creating a new Maven Project
```
mvn archetype:generate \
-DarchetypeGroupId=software.amazon.awssdk \
-DartifactId=my-app \
-DarchetypeArtifactId=archetype-lambda -Dservice=s3 -Dregion=EU_NORTH_1 \
-DarchetypeVersion=2.21.29 \
-DinteractiveMode=false \
-DgroupId=com.example.myapp

```
