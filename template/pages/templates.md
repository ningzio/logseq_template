public:: true

- # journal template
  template:: journal
  template-including-parent:: false
	- ## 👋 Hi~
		- How's the weather today?
			- ☁️ ☔️ ⛅️ ☀️ 🌀 ❄️
		- Sleep well last night?
			- 😄 😒 😐 😭
		- how are you feel today?
			- 😄 😐 😡 😭
	- ---
	- ## 💪  What need to do today
		- {{query (todo todo later doing now)}}
		  query-sort-by:: block
		  query-table:: false
		  query-sort-desc:: true
	- ---
	- ## 📝 Today's plan
		-
	- ---
	- ## 🏆 What did you do today?
		-
	- ---
	- ## ✍️ Things you want to remember
		-
- ---
- ## Meeting
  template:: meeting
	- 📌 **Topic**:
	-
	- 🕙 **Time**:
	-
	- 👥 **Participants**:
		-
	- 📢 **Discuss**:
		-
- ---
-
-