# How to Update ARK Progress Tracker

This file explains how to maintain continuity across ChatGPT threads.

---

# 1️⃣ When to Update

Update the tracker when:

- A topic is fully understood
- A concept needs revision
- You implemented something
- A thread becomes long
- You are moving to a new chat
- You are blocked

---

# 2️⃣ Allowed State Values

Always use one of these states:

NOT_STARTED
IN_PROGRESS
REVISION
IMPLEMENTING
BLOCKED
COMPLETED

Do not invent new state names.

---

# 3️⃣ How to Move Between States

NOT_STARTED → IN_PROGRESS  
IN_PROGRESS → COMPLETED  
IN_PROGRESS → REVISION  
IN_PROGRESS → BLOCKED  
COMPLETED → REVISION (if confidence drops)  
COMPLETED → IMPLEMENTING (when applying in code)

---

# 4️⃣ Before Starting a New Thread

1. Update:
   - Current Phase
   - Current Step
   - Learning State
   - Last Completed Topic
   - Next Planned Topic

2. Update notes section for the current topic.

3. Copy the entire tracker file.

4. Paste it into the new thread.

5. Type:

   Continue ARK from tracker.

---

# 5️⃣ If Blocked

Set:
Learning State: BLOCKED

Add:
- Exact error
- What you tried
- Repo link (if applicable)

---

# 6️⃣ GitHub Integration Rule

Whenever you push code:
- Update Implementation Log
- Add commit link
- Set relevant module to IMPLEMENTING or COMPLETED

---

# 7️⃣ Self-Assessment Rule

After finishing each Phase:
Update confidence score.

Be honest. This is for growth.

---

# 8️⃣ Thread Continuation Rule

Never start a new thread without pasting the tracker.

The tracker is the single source of truth.