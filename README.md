# Function-Calculator-App

Using Http Trigger to call an Azure-Function-App that sums the value of x and y and inputs a result The app is tested locally and later published to Azure and also tested in Azure using http as it's trigger. The class was renamed to sum The function attribute was also renamed to sum The content of run method was deleted The logger was not deleted Lines as shown below were added int x =int.Parse(req.Query["x"]); int y =int.Parse(req.Query["y"]);

int result = x + y;

return new OkobjectResult(result);

The parseInt method parses a value as a string and returns the first integer

more information about partInt can be gotten from this link https://www.w3schools.com/jsref/jsref_parseint.asp

the sum was calculated in the local environment using the link that was thrown to the debugger http://localhost:7071/api/sum?x=4&y=6
