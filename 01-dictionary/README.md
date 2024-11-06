# JavaScript Reboot

Run the following commands to begin the first challenge

```shell
# navigate to the first folder
mkdir -p ~/code/javascript-reboot/01-dictionary/

# open up the challenge folder in VS code
code .

# serve the file
serve
```

## Objectives

For this part of the challenge we basically want to run the exact same challenge as yesterday. _Easy right_? But `ids` and `selectors` have changed, positions have shifted. Can you understand the context of what is going on and apply the right knowledge?

## Specs

There are a few parts to the whole challenge, but we only want to focus on just this one first.

When dealing with a challenge like this, let's think of what happens first.

#### User Flow

```text
1. User will type something in
2. User submits the form
3. User sees the results on the page
```

So it's a 3 step process for them. It might be more for us, but let's see if there's anything we can do for each step.

**1. User will type something in**
There isn't really much for us to do now, just need to take note of **where** the user is inputting his text.

**2. User submits the form**
Now this is something we can test.
How would we break this down into micro steps?

- Can we select just the form element?
- Can we ensure we can do something when the user submits the form?
- On submit, can I get what the user has typed as his input?
- Switching tasks, now that I can get the user's input, can I make a fetch request to the endpoint **with a hardcoded value**?
- Now that I know the url is correct, can I update the url with the users input?

**2. User sees the result on the page**

- Since I can get back what I want, how do I update the html with the data I get back?