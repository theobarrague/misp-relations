# misp-relations
`names=$(cat definition.json | jq '.values[].name'  | sort) && echo $names && echo $(echo $names | wc -l) relationships are defined` 
