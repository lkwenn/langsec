dating-server:
	$(TROUPE)/bin/troupec dating-server.trp -o ./out/dating-server.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-server.js --id=../ids/id-server.json --trustmap=../trustmaps/GoT.json --aliases=aliases.json

dating-alice:
	$(TROUPE)/bin/troupec dating-client-alice.trp -o ./out/dating-client-alice.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client-alice.js --id=../ids/alice.json --trustmap=../trustmaps/client-alice.json

dating-bob:
	$(TROUPE)/bin/troupec dating-client-bob.trp -o ./out/dating-client-bob.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client-bob.js --id=../ids/bob.json --trustmap=../trustmaps/client-bob.json

dating-mallory1:
	$(TROUPE)/bin/troupec dating-client-mallory1.trp -o ./out/dating-client-mallory1.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client-mallory1.js --id=../ids/mallory.json --trustmap=../trustmaps/client-mallory.json

dating-mallory2:
	$(TROUPE)/bin/troupec dating-client-mallory2.trp -o ./out/dating-client-mallory2.js
	node $(TROUPE)/rt/built/troupe.js -f=./out/dating-client-mallory2.js --id=../ids/mallory.json --trustmap=../trustmaps/client-mallory.json
