function generatePlayerNameFields(){
	
	//Get the number of players from the dropdown box
	var numberOfPlayers = document.getElementById("numberOfPlayers").value;
	//The container where the player name fields will go
	var container = document.getElementById("container");
	//Clear the previous container
	while (container.hasChildNodes()){
		container.removeChild(container.lastChild);
	}
	
	for(i=0;i<numberOfPlayers;i++){
		container.appendChild(document.createTextNode("Member " + (i+1)));
		var input = document.createElement("input");
		input.type = "text";
		input.name =  "member" + i;
		container.appendChild(input);
		container.appendChild(document.createElement("br"));
	}
}