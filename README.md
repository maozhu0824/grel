# grel
# Support two syntaxes 
# 1. value.function(options)
# 2. function(value, options)
toUppercase(value)
value.toUppercase()

toLowercase(value)
value.toLowercase()

toTitlecase(value)
value.toTitlecase()

# remove any white space characters from the start or end of the current value
trim(value)   
value.trim()

substring(value,0,4)
value.substring("a","b")

replace(value,"a","b")
value.substring("a","b")

"Prefix:" + value

# Data types in Open Refine
# "Boolean"
value.contains("test")
# Array
["Monday","Tuesday","Wednesday"]
value.split(",")
value.split(",").sort()
value.split(",")[0]
value.split(",").sort().join(",")








