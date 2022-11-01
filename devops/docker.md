### Docker cheat sheet
Break down of the dicker run command:

Example: 'docker run --rm -d -p 8080:80 --name web nginx'

And you may open the web service in your browser at 'localhost:8080' to see it running.

To stop the container with SIGTEM 'docker stop web'

To stop the container with SIGKILL 'docker kill web'