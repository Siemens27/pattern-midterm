### Getting Started
#### Step 1: Clone this Repository
`git clone https://github.com/siemens27/BankApplication` 
#### Step 2: Build & Run
```shell
./mvn clean package
java -jar target/BankApplication-<current version>-jar-with-dependencies.jar
```

### Development
You'll need to use Netbeans for development, this IDE was chosen because it is widely used by most programmers due to its excellent tools for design forms of the Swing GUI.

No database is required to be installed, since this project is using the H2 Database, and all the data will be generated on the home folder of the project ~/.zweibank/db (Unix) or C:\\zweibank\\db (Windows). You can open the console of the database when the application is running by looking into http://localhost:8082.
Enjoy!
