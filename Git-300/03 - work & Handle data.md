Contextual instructions <br>
    - Chat<br>
    - .github/copilot-instructions.md <br>
    - Code snipet<br>
    - open files<br>

UserPrompt -> preprocessed in Copilot Chat ->  Contextual instructions -> Proxy server -> Large Language Model -> proxy server

<br>

- Proxy server - toxic language, prompt hacking, attempt to trick the model <br>
               - applies a final layer of checks to ensure code quality, security, and ethical standards. (reply) <br> 
               - Admin can enable matching public code filter (150) <br>

- GitHub Copilot does not retain code suggestions made in the IDE as it is discarded after being served.<br>


** #Organizantion Filter **
    - Code Matching Filter - to avoid suggestion matching public code



