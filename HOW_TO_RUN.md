require python>=3.10 (install python lastest version: https://www.python.org/downloads/)  
run  
cd <name_project>  
venv\Scripts\activate  
python manage.py runserver  
(if errors, web3 need C++ Build Tools, MSVC v143 - VS2022, Window 10 SDK or 11 SDK install vs_BuildTools at  
https://download.visualstudio.microsoft.com/download/pr/f602e0ef-3c65-4237-8b0c-c173ab1c5aff/50a7fc844a52de79c22004fd24cc5272c4f16d55ed6b6694d0c767dde6babbac/vs_BuildTools.exe). 
web3.py depends on several C-based libraries such as: cytoolz, lru-dict, eth-hash(which uses pysha3),...
   
