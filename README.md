# swiggy_totalspent
The swiggy script retrieves all your swiggy orders and calculates the toal money you spent on swiggy.com.  The zomato retrieves all your zomato orders and calculates the toal money you spent on zomato.com.  Also shows the number of orders and average money you spent on each order
How to use
The script expects you to give your swiggy session as input.

Login to swiggy.com or zomato.com on a browser (chrome or firefox)

Install the Cookie Editor chrome extension or the Cookie Editor firefox extension

Go to the Swiggy tab or Zomato tab and click on the Extension's icon, and select "Export". This will copy your cookies to clipboard
Create a new file called cookies.json in the same directory as the swiggy.py script or zomato.py script and paste the copied cookies into this file.

Install requirements with pip

pip install -r requirements.txt
Now simply run swiggy.py to get swiggy orders

python swiggy.py
Now simply run zomato.py to get zomato orders

python zomato.py
