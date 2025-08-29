Python Screening Task 2: Write a Prompt for an AI Debugging Assistant


Python Screening Task 2: AI Debugging Assistant Prompt
This repository holds my submission to the Python Screening Task 2. The assignment involves writing a prompt for an AI debugging assistant that can assist students in debugging Python code without exposing the correct solution. On the next page, you will see the prompt, a description of design decisions, responses to the mandatory reasoning questions, and setup information.

Submitted Prompt:

You are a debugging assistant working with an AI to assist a Python student in debugging their code. Your task is to review the given code, determine if there are any issues, and offer constructive, student-oriented advice on how to locate and correct bugs without actually providing the solution. Observe these guidelines:

- Start off with a positive, encouraging statement to improve the confidence of the student, e.g., "Good work on your code! Let's go through a few places and get it even better."
- Pinpoint one or two most significant issues in the code by describing what was seen happen, or what the error was, but not describing the actual repair.
- Provide suggestions in the form of open-ended questions that challenge the critical thinking of the programmer, like "What do you anticipate this variable to be here?" or "Can you test how this loop is working with various inputs?"
- Provide real-world debugging strategies, such as adding print statements, verifying variable types, or dividing the code into smaller pieces.
- If the problem concerns a Python principle (e.g., list indexing, scope), give a simple, student-friendly definition of the principle without applying it directly to the code.
- Be friendly and supportive in tone, refusing to use difficult jargon where it is not clearly explained.
- Do not give fixed code or direct solutions—aim to point the student in the direction of finding the solution themselves.
- End with a positive note, inviting the student to attempt your recommendations and seek additional assistance if necessary.

Your response should be brief, clear, and centered around enabling the student to learn through debugging.

Explanation of Design Choices

Why I Worded It the Way I Did:

The prompt is designed with definite, actionable instructions in bullet form to make the AI realize its function and adhere to a uniform method. It utilizes direct language such as "analyze," "identify," and "provide guidance" to establish the task, while samples (e.g., particular questions or phrases) exemplify the intended behavior. The stress on "student-friendly" and "promoting critical thinking" is in consonance with learning objectives, and hence, the prompt can be made responsive to multiple scenarios of Python debugging.

How I Made It Avoid Giving the Solution:

The instruction clearly says "Do not provide corrected code or explicit solutions," establishing a clear boundary. It instructs the AI to apply indirect tactics such as open-ended questions and generic explanations of problems (e.g., "observed behavior") instead of identifying fixes. By emphasizing debugging techniques and general explanations without direct implementation, the AI leads students to solutions without solving the problem for them.

How It Promotes Constructive, Student-Centered Feedback:

The prompt requires a positive, encouraging tone with the first encouraging comment and a final call for follow-up, providing a safe space for learning. It requires brief, jargon-free answers and explanations suitable for beginners to maintain accessibility. By proposing realistic debugging strategies and questions that promote critical thinking, it enables students to take charge of their learning yet feel guided.
Reasoning (Required Answers)
What Tone and Voice Should the AI Adopt When Responding:

The AI must adopt a polite, supportive, and non-threatening tone, that of a patient instructor, to encourage students and minimize frustration. Phrases such as "Great effort!" or "Let's figure this out together" create a positive atmosphere. The style must be plain, conversational, and to the point, using simple words and defining any technical jargon (e.g., "scope") in a straightforward manner.

How Should the AI Balance Between Detecting Bugs and Leading the Student:

The AI can devote around 20-30% of the response to bug identification by mentioning symptoms or broad problem areas (e.g., "The output appears to be wrong here") without elaborating on the solution. The rest of the 70-80% should be devoted to direction through questions (e.g., "What would you see if you printed this variable?"), debugging hints, and applicable concepts. Flagging one or two issues at a time keeps feedback tight and easy to follow, promoting self-learning.

How Would You Modify This Prompt for Novice vs. Expert Learners:

For novice learners, I would include: "Use extremely simple language, define basic Python concepts (e.g., 'variable' or 'loop'), and emphasize common mistakes such as syntax or elementary logic. Recommend visual debugging tools such as flowcharts." This guarantees accessibility. For more advanced learners, I would change it to: "Assume knowledge of Python basics and recommend advanced debuggers such as pdb or performance analysis. Investigate more complex issues such as coding efficiency or boundary cases." This is more technical, detailed feedback without solutions.