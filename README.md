# ALXprodev-Devops

---

### Task 0: API Request Automation.

The objective is to automate the process of making API requests to the Pokemon API and saving the result to a file.

* Writing a shell script that makes a request to the [Pokemon API](https://pokeapi.co/api/v2/pokemon/) and retrieves data for a specific Pokemon Pikachu. It should save the response to a json  file: `data.json` and if the request fails , it should log the error to an error file: `errors.txt`.

---

### Task 1: Extract Pokemon Data.

 The objective is to use advanced text manipulation  tools (`jq`, `awk`, and `sed`) to extract specific data from the API response.

 *  Writing a script that extracts the Pokemon's name, height, weight and type from the json file created in Task 0 and format the ouput in a human-redable way. `Pikachu is of type Electric, weight 6kgs, and is 0,4m tall.`

---

 ### Task 2: Batch Pokemon Data Retrieval.

 The objective is to automate the retrival of data for multiple Pokemon and store it in separate files.

 * Creating a script that loops through a list of Pokemon [Bulbasaur, Ivysaur, Venusaur, Charmande, Charmeleon].

 ### Task 3: Summarize Pokemon Data.

 The objective is to create a report that summarizes data for multiple Pokemon.

 *  Writing a shell script that reads all the JSON files generated in Task 2 and extracts the name, height and weight of each Pokemon and then generating a CSV file.
