./ApplicationName
|
|______	src/
|		|______	com/
|				|______	example/
|						|______	Main.java
|
|______	bin/
|		|______	com/
|				|______	example/
|						|______	Main.class
|
|______	README.md


-----------------------------------------------------------------
|Interpret	|	$ javac -d bin src/com/example/Main.java	 	|
|---------------------------------------------------------------|
|Run		|	$ java -cp bin com.example.Main					|
-----------------------------------------------------------------