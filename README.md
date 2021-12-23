# schema-generation
Generate postgresql db schema from existing database using SchemaSpy

java -jar schemaspy-6.1.0.jar -t pgsql -s public -db dbname -u username -p pwd -host localhost:5432 -o <output directory> -dp ./postgresql-9.4.1208.jre6.jar
