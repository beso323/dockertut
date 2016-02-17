# dockertut
Simple docker tutorial

# Build image
<pre>docker build -t [REPO]:[TAG] .</pre>

This builds a docker image with specified repository and tag.  The . stands for the location of the Dockerfile

# Push image
<pre>docker push [REPO]:[TAG]</pre>

# Tag image
<pre>docker tag [image hash] [REPO]:[TAG]</pre>

# Get logs (follow)
<pre>docker logs (-f) [process hash]</pre>
