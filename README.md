<h1 align="center">
    <img src="https://github.com/user-attachments/assets/938d8206-f29a-474a-b058-347629e89459" width="40%"  />
  <br/>
  <br/>
  <strong>Lagged to MVP</strong>
</h1>

<p align="center">
  "Instead of speeding you up, these list get you distracted of your main goal."
</p>

<p align="center">
  A growing list of stuff, concept, and tools that is very solid to have, but usually slows you down on your MVP phase and keeps you distracted.<br/>
  Consider them once you've secured your MVP phase.
</p>

<p align="center">
  Open for contributions!
  <br/><br/>
  <em>See also <a href="https://github.com/Xavier-IV/rapid-to-mvp">Rapid to MVP</a></em>
</p>

<br/>

The format are as follows:
- Rough explanation of why its bad (for MVP). Sometimes there's sarcasm.
- When you should revisit this
- What you should use...for now.


## Unit Test & E2E

Even though they're good and recommended in big corporate, but with 0 users or customers, they're a distraction for an MVP phase.

*When to revisit*: Once your codebase started to grow and you lose track of what changes did what. Or when you start to lose track of business domain logic.

*What to use for now*: Take note of hotspot for heavy business logic, one day you WILL visit it with much needed tests.

## Too Detailed Infrastructure

As much as interesting it is to talk about cloud infra in your company daily standup or presentation, as a solo dev, let's leave it at the learning doorstep. Only exception is if you're experienced in this topic.

*When to revisit*: Once you've scaled to hundreds or thousands of customer, and receive complaints.

*What to use for now*: Plain old boring deployment services.

## Over-Engineering

Building a complex and highly scalable architecture might seem appealing, but it's overkill for an MVP. Focus on getting a working product out instead.

Even if you're experienced, this usually gets the best of us (even the experts).

*When to revisit*: When your product starts to struggle under real-world load or when performance bottlenecks become evident.

*What to use for now*: Keep it simple, silly.

## Perfecting the UI/UX

Spending excessive time refining the design and user experience is tempting, but it's not necessary in the MVP stage. Aim for functional, not flawless. No one will complain, if there's no one using your product.

Unless you have background in UI/UX, even so, keep it in check.

*When to revisit*: When you have user feedback pointing out specific UI/UX issues, or when you're ready for a broader audience.

*What to use for now*: Reuse whatever a UI library gives you, and try to make do with it.

## Extensive Documentation

While documentation is important, writing exhaustive documentation for an MVP can be time-consuming and isn't essential at this stage. You're the only developer anyway.

You might be a docs guru, but save it when you started to hire/onboard more members

*When to revisit*: Once the product is stable and you start onboarding more developers or contributors.

*What to use for now*: Write good and readable, self explanatory codes. Take note of code hotspots for business domain.

## Multi-Platform Support

Supporting multiple platforms (e.g., web, mobile, desktop) right from the start can slow down development significantly. Focus on one primary platform. Who's going to maintain all that codebases? You.

*When to revisit*: When you have a solid user base on one platform and demand for others is clear. Also when you have right amount of developers to support it.

*What to use for now*: Whatever your main customer base are using.

## Fancy Tech Stack

Choosing cutting-edge or niche technologies can slow down your progress due to the learning curve and potential integration issues. Stick with what you know works.

I know, everyone's talking about that X framework.

*When to revisit*: When your MVP gains traction, and you have the bandwidth to experiment with newer technologies.

*What to use for now*: Whatever you're strong at using, especially with working experience.

## Tools Pivoting

Pivoting on a framework or tool you use can drastically slow down your MVP. Even if you found something you hate on that tools/framework, try your best to resolve it.

Big corporation do pivot a framework or tools, but it usually cost multiple developers to develop and quarters to years to finish.

Whenever you're attracted to new fancy tools, keep your eyes on the wheel. MVP.

*When to revisit*: Most likely you won't need to pivot your tools, except for costs, security, resources, support and end-of-life tools. 

*What to use for now*: Whatever framework/tools you used at first, hold that itch.

## Early Refactoring

I did this a lot of time personally. Refactoring stuff that works great already. What a great engineer I am right? But I still have 0 users.

*When to revisit*: Ideally, when your codebase grew. Or when the repeatition outgrew you.

*What to use for now*: Whatever bad codes you wrote, just use it. As you continue writing code, learn some good code practice as well. Don't fix bad tyre with bad tyre.
