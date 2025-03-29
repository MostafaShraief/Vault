---
banner: Images/pick-up-car.png
banner_y: "77"
sticker: lucide//car
aliases:
  - Driving Vehicle License Department
  - Course 19 Project
  - MS SQL
  - C#
color: var(--mk-color-blue)
---
# Links
## Project solution
	file:///D:/Programming/Projects/DVLD/DVLD.sln
## GitHub Repo
	https://github.com/MostafaShraief/DVLD

# Commits
## commit script (3/26/2025):
```
i have done tasks and fixed some bugs, i can not remember all of them because i have left the project a long time because I participated in a hackathon.
Done:
1. add edit local license
2. show local license list
3. ucList (this is dynamic list that will reduce more code and any change on it will reflect to all connected lists)

Next Steps:
1. fix add more than one license class to the same person (done)
2. show local license info (done)
3. delete local license (canceled)
```

## commit script(3/29/2025 3:05 AM):
```
completed:
1. fix add more than one license class to the same person.
2. show local license info.

fixed:
1. bug when open test types list form.
```

# next video:
## Applications: Local Driving Application Part 2:

- Drivers list
Context menu:
- delete license
- eye test 
- written (theory) test
- practical (street) test
- issue license
- show license
- show person license list history

Notes:
1. You can't cancel completed license, delete it, schedule test or issue license ^p8p5ht
2. First test not include retake test fees, after first test there is fees for retaking
3. you can not retake same test if you pass it in the current application id
4. You can retake tests as you want while u r not passed it
5. Every schedule test is showed the same thing, like test appointments form and retake test form.
6. test appointments include: local license info, add test and table of tests failed-passed ^tu90ya
7. Retake test form: schedule test and retake test info ^4wg0yt
8. You can't issue test till you pass all tests (3)
9. Same for show license (till u issue it)
10. show license info + show license list history + issue license forms 

steps:
1. Drivers List, add, edit, etc. ![[{8726D7DD-C5EE-4F2F-8EB8-2527A609A018}.png]]
2. enable features in context menu to reduce confusing include:
	1. person history always enabled
	2. schedule test for new local license, it depends on passed tests, where:
		1. 0 = enable eye (theory) test
		2. 1 = enable written test
		3. 2 = enable practical (street) test
		4. 3 = enable issue license - disable schedule test + show license
	3. after completed status (issue license) is shown, you can show license (enable it - disable schedule + issue license)
	4. [[DVLD#^p8p5ht]]
	5. canceled status: enable show app details + delete app + 1.
3. person license history form ![[{1279529E-A402-44DF-9B54-F497ED8166F7}.png]]
4. schedule license:
	1. generic form includes:
		1. [[DVLD#^tu90ya]] ![[image.png]]
		2. [[DVLD#^4wg0yt]] ![[image-1.png]]
	2. add (eye test -> written test -> practical test) processes
5. issue test form ![[{0726F4CC-F384-4588-948A-14DCFCAFEFB9}.png]]
6. show license form
![[{313844B8-1671-4CD9-9AEA-9F8661C9FD45}.png]]
7. delete license