 Otrzymujemy i wyprowadzamy całą listę kontaktów w postaci tabeli (console.table)
node index.js --action list
https://monosnap.com/file/TV5DLqFA6U6lTjEH1mSivpqJmPF24W

# Otrzymujemy kontakt po id
node index.js --action get --id 05olLMgyVQdWRwgKfg5J6
https://monosnap.com/file/TGNSsXSqwBvWRQt6W4feEqcTedygCi

# Dodajemy kontakt
node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
https://monosnap.com/file/uy2Ka05j81eOK0CAvi0DVx4FgouIqO

# Usuwamy kontakt
node index.js --action remove --id qdggE76Jtbfd9eWJHrssH
https://monosnap.com/file/E6gTVqGhFd76PdK1afdJrPGTPsoIrA