# YAGNI 

“YAGNI” stands for “You Aren’t Gonna Need It”. YAGNI is a principle that encourages developers to avoid adding features or functionality to a system until they are explicitly required. It is based on the premise that adding unnecessary features can lead to:

- 📈 Increased complexity
- 🕒 Longer development times
- 🐞 Potentially more bugs 

Instead, developers should focus on delivering the simplest solution that meets the current requirements.



###  Before YAGNI
 ![carbon](https://github.com/HarisChandio/YAGNI/assets/86180280/f3b9e417-8790-4fc8-bb8e-0ee415f5116b)


### After YAGNI
![carbon (1)](https://github.com/HarisChandio/YAGNI/assets/86180280/de0de850-1c8b-4c16-bf5f-e72ae3331f33)




## Why Devs should follow YAGNI

- 💰 **Cost of Building**: Time, effort, and resources spent creating features.
- ⏳ **Cost of Delay**: Economic impact of not delivering promptly.
- 🏋️‍♂️ **Cost of Carry**: Ongoing difficulty and extra work from feature complexity.
- 🔧 **Cost of Repair**: Ongoing cost to fix development mistakes or bugs.

## Example : Simplifying API Endpoints in Django
### Assume for now you just have to create a general purpose dashboard for all types users.
### Before YAGNI:
![carbon (2)](https://github.com/HarisChandio/YAGNI/assets/86180280/97abb3b1-0a70-40d2-8393-3ed85c8e03d6)


### After YAGNI

![carbon (3)](https://github.com/HarisChandio/YAGNI/assets/86180280/c039975e-2870-4692-8c3f-061665bab229)



### Explanation
**Before YAGNI**:

- Separate view classes for different user roles (AdminDashboardView, UserDashboardView, GuestDashboardView).
- This separation adds unnecessary complexity without clear current requirements for role-specific dashboards.

**After YAGNI**:

- A single DashboardView class to handle the dashboard endpoint.
- Simplifies the API by avoiding premature optimization and complexity.
- Role-based logic can be added later if the need arises.



## Why YAGNI is Important

YAGNI is important because it helps to keep software development focused and efficient. By only implementing features that are necessary, developers can avoid wasting time and resources on unnecessary functionality. This can lead to faster development times, reduced complexity, and a more maintainable codebase.

![image](https://github.com/HarisChandio/YAGNI/assets/86180280/08df63ce-e6df-4cc3-9555-fcb555e74c9c)

### How do I use YAGNI in my code?

To use YAGNI as a developer, it’s like having a practical guide to keep your work focused and efficient.

![image](https://github.com/HarisChandio/YAGNI/assets/86180280/eb3daaec-5e04-4731-9077-8dc4bcf85a1e)

### Examples of YAGNI
Examples of YAGNI
Here are some examples of how YAGNI can be applied:

- 🛑 **Feature Creep Avoided**: A development team is working on a web application. They initially plan to include a feature that allows users to create and share custom avatars. However, after considering the time and resources required to implement this feature, they decide to postpone it until they receive feedback from users indicating that it is necessary.
- ⚙️ **Complexity Reduction**: A developer is working on a mobile app that allows users to track their exercise routines. Initially, they plan to include a feature that automatically generates personalized workout plans based on the user’s fitness goals. However, after considering the complexity of implementing this feature and the potential impact on the app’s performance, they decide to stick with a simpler approach that allows users to create their own workout plans manually.
- 💼 **Resource Allocation**: A development team is working on an e-commerce platform. They initially plan to include a feature that allows users to create Wishlist and share them with friends. However, after considering the limited time and resources available for the project, they decide to focus on just creating a wishlist and other features that are more critical to the platform’s success.


### Benefits of YAGNI

- ⏩ **Faster Development**: Avoid unnecessary features, expedite development.
- 🧩 **Simplicity**: Keeps codebase simple, easy to maintain.
- 🔄 **Flexibility**: Adaptable codebase for changing requirements.
- 🛡️ **Reduced Risk**: Fewer unnecessary features, fewer bugs.
- 🎯 **User Focus**: Implement only essential features for users.
- 💵 **Cost Savings**: Save time, resources by avoiding extras.
- 🔧 **Improved Maintainability**: Simpler codebase, easier maintenance.
- ⭐ **Better User Experience**: Prioritize essential features, enhance user experience.

