# Fetch-API-to-Response-Object


## The code to construct a Fetch API that parses the response stream as a JSON object.

### Code:

    fetch('url-that-returns-JSON')
    .then(
      response => response.json();
    ).then(jsonResponse => {
      console.log(jsonResponse);
    });
