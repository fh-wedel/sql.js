fh-abbild.base64: fh-abbild.sqlite
	openssl base64 -in fh-abbild.sqlite -out fh-abbild.base64

fh-abbild.sqlite: fh-abbild.sql
	sqlite3 fh-abbild.sqlite ".read fh-abbild.sql"

clean:
	rm -f fh-abbild.sqlite fh-abbild.base64
