# Troubleshooting 

Problems I ran into while trying to get this to work 

## Mismatch in checksum

Not sure. Repairing among other things didn't fix it. Maybe just delete the database and start over? I managed to circumvent this by just doing stuff in a new database with a different name. 

IMPORTANT: Intellij looks at a different directory than the terminal does, so if you try to run on intellij, postgres needs to be set up there in the same way as WSL2. 