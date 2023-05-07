# CoinsAPI (API lib ref)
Library that references the CoinsAPI for use in Maven projects.

**WARNING:** THIS IS NOT THE PLUGIN. DUE TO THE TERMS THE PLUGIN CANNOT BE DISTRIBUTED OR MODIFIED. THE ONLY CLASS IN THIS LIBRARY ONLY REFERENCES THE API. DO NOT INVOKE THIS CLASS AT RUN TIME, ITS SCOPE IS ONLY PROVIDED AND DOING SO WILL THROUGH AN EXCEPTION.
## Setup
### Step 1: Add the repository
```xml
<repositories>
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
</repositories>
```
### Step 2: Add the dependency
```xml
<dependency>
  <groupId>com.github.Altzenck</groupId>
  <artifactId>CoinsAPI-api-lib-ref</artifactId>
  <version>1.8.9</version>
  <scope>provided</scope>
</dependency>
```
