# Lavacoin-Mining-Pool
A Pool for Mining Lavacoin

Will have to do the following until I figure out how to fix it.  I'm not a programmer, much respect, but I'm trying.

Follow the instructions from b.	https://github.com/zone117x/node-cryptonote-pool
When you get to the section that deals with 'npm update' you have to change the version of vm to v0.10.48.
Follow these instructions:

        a.	rm -rf node_modules/
        
        
        b.	nvm install v0.10.48
        
        
        c.	npm update
        
        
        d.	npm install cryptonote-util (have to load new one         
                https://github.com/fancoder/node-cryptonote-util.git
                
        
 
        e.	npm install bignum
        
        
        
    That should process without any errors, at least as tested on Ubuntu Linux x64 16.04 LTS.
    
