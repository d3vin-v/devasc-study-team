so graphhopper_parse-json_7.py doesn't work, because of the code added in part 5 of the 4.9.2 lab.
i have the three line commented out in the master branch they are:

        paths_status = requests.get(paths_url).status_code 
        paths_data = requests.get(paths_url).json()
        print("Routing API Status: " + str(paths_status) + "\nRouting API URL:\n" + paths_url)

i spent hours thrying to figure this out

ive put the version ive been using in the dev branch
