# Requirements Analysis


### A. Define the Application's Purpose

- **Problem Statement:**
	- Climbing gyms have begun to adopt a system in which climbers can write their contact information down on a note card and post it to a bulletin board dedicated to finding belay partners. This is a great idea, however it is inefficient. By digitizing the traditional note card bulletin boards in climbing gyms, Belay Partner Connect can bring efficiency, security, and community engagement to a whole new level.
- **Project Summary:**
	- BPC connects climbers and community together by making it easy to find a belay partner, someone to go bouldering with, or create a climbing group.

### B. Identify User Roles and Permissions

- **Users:**
	- Climbers
	- Group Admins
	- Gym Admins
- **User Permissions:**
	- Climbers: Use the core features of BPC
		- Verified Climber Badge: Climber was verified by their gym(s)
		- Assistive Partner Badge: Badge of certification for climbers trained to assist visually impaired climbers
	- Group Admins: Users who create and manage climbing groups within the app might have specific permissions to administer their groups.
	- Gym Admins: An administrative account for a climbing gym.
		- Grants verification for Climbers (however, I can do this myself too)
		- Creates and manages events through BPC

### C. Outline All Features

1. Profiles
2. Message Board
3. Events
4. Groups
5. Belay someone with a visual impairment
6. Support and Contribution

	#### 1. Profiles
	
	- **Verification Icon for Verified Climbers:**
	    - Functionality: Shows a special icon if the climber is verified by their climbing gym.
	    - Rules: Verification requires gym authentication.
	    - Priority: Essential for trust-building.
	- **Skill Level:**
	    - Functionality: Allows users to display their climbing grade level.
	    - Priority: Essential for matching.
	- **Toggle 'In Need of Belay Partner' Icon:**
	    - Functionality: Users can set specific dates for when they want a partner.
	    - Priority: Essential for functionality.
	- **Profile Picture, Bio, Interests:**
	    - Functionality: Personalize the profile with images and interests.
	    - Priority: Add later for enhanced user experience.
	- **Auto-Match Button:** Provide a button for users to be automatically matched with a climbing partner based on skill level and other metadata.
	
	#### 2. Message Board
	
	- **Climbers' Casted Requests:**
	    - Functionality: Displays climbing rating range and dates for climbing.
	    - Priority: Essential for planning.
	- **Private Messaging, Confirm Date and Time:**
	    - Functionality: Allows climbers to communicate and set plans.
	    - Priority: Essential for planning.
	- **Notifications:**
	    - Functionality: Alerts users to messages or confirmations.
	    - Priority: Add later for convenience.

	 # 8. **Events:**
	
	- **Create and Host Events:**
		- Allow users, groups, or even climbing gyms to create and host climbing-related events.
	- **Join/Leave Events:**
		- Include options for users to join or leave events.
	- **Event Details Page:**
		- Each event should have a detailed page with information about the event, including date, time, location, organizer, skill level required, etc.
	- **RSVP and Participant List:**
		- Enable RSVP functionality and display a list of participants attending the event.
	- **Event Calendar:**
		- Provide an overall calendar view to see upcoming events.
	- **User Notifications:**
		- Implement notifications for event updates, reminders, or changes.
	- **Event Categories and Filters:**
		- Offer various event categories (e.g., competitions, workshops, social climbs) and filters to help users find events that interest them.
	- **Integration with External Calendars:**
		- Allow users to export event details to their personal calendars (like Google Calendar or iCal).
	- **User-Generated Content and Photos:**
		- Enable attendees to share content or photos from the event, fostering community engagement.
	- **Event Feedback and Reviews:**
		- Include a feature for attendees to provide feedback or reviews after the event.

	#### 4. Groups
	
	- **Create, Join, Leave, Message Groups:**
	    - Functionality: Allows users to form and manage climbing groups.
	    - Priority: Essential for community building.
	- **Suggest Date(s) to Climb:**
	    - Functionality: Propose and agree on climbing dates within the group.
	    - Priority: Essential for group coordination.

	### 4. Belay Someone with Visual Impairment:
	
	- **Certification for Belaying Visually Impaired Climbers:** Allow climbers to get certified to belay someone with visual impairment.
	- **Course Creation (if needed):** If no certification exists, provide resources or a platform to create a course for this skill. <-check on this.
	
	### 5. Support and Contribution:
	
	- **Buy Me a Coffee Link:** Include a link for users to contribute to the site's creator (me) as a form of support.

### D. Consider Legal and Ethical Implications - Accessibility

- **Research Regulations:** Especially around the belaying paraclimbers, find relevant laws or industry guidelines.
- **Consult with Experts if Needed:** If there are complex legal considerations, seeking professional advice is wise.

### E. Create User Stories

- **Write User Stories:** For each feature, create user stories that describe how a user will interact with that feature.
- **Include Acceptance Criteria:** Define the criteria that must be met for the feature to be considered complete.
	
	#### Profiles
	
	- **As a registered climber, I want to verify my account with my climbing gym so that other users know I'm a legitimate climber.**
	    - Acceptance Criteria: The user can submit verification proof, the climbing gym (or BPC if partnered w/ climbing gym & has access to gym's live user database) can confirm verification, and a verification icon appears on the user's profile.
	- **As a climber, I want to toggle on/off the 'in need of belay partner' icon so that others know when I'm looking for a partner.**
	    - Acceptance Criteria: The user can easily switch the status, the status is visible to others, and it allows setting specific dates.
	
	#### Message Board
	
	- **As a climber, I want to post requests for climbing partners, specifying the climbing rating range and date, so that other climbers can respond.**
	    - Acceptance Criteria: The user can post requests with the necessary details, the requests appear publicly, and other climbers can respond privately or confirm the date and time.
	#### Events
	
	- **As a user, I want to browse upcoming climbing events so that I can find gatherings, competitions, or workshops that interest me.**
	    
	    - Acceptance Criteria: Users can view a list or calendar of events, filter by type, date, or location, and see essential details of each event.
	- **As a user, I want to create and manage my own climbing events so that I can invite others to join.**
	    
	    - Acceptance Criteria: Users can create events with relevant details (e.g., date, time, location, type), edit or delete them, and see who plans to attend.
	- **As a climbing gym or event organizer, I want to promote my events on the platform so that I can attract more participants.**
	    
	    - Acceptance Criteria: Organizers can create an organizer profile, list events with full details, and receive inquiries or RSVPs from interested climbers.
	
	#### Groups
	
	- **As a user, I want to create, join, leave, or message a climbing group so that I can plan group climbing activities.**
	    - Acceptance Criteria: Users can perform all mentioned actions, and group activities are easily managed and communicated.
	
	#### Belaying Someone with a Visual Impairment
	
	- **As a climber, I want to get certified to belay someone with a visual impairment so that I can offer my services to those who need it.**
	    - Acceptance Criteria: The user can apply for certification, complete the necessary training, and have their certification status visible on their profile.
	
	#### Buy Me a Coffee
	
	- **As a satisfied user, I want to support the site by buying the creator a coffee.**
	    - Acceptance Criteria: Users can find and click the link to pay, complete the payment, and receive a thank-you message or acknowledgement.

### F. Develop a Requirement Document 

- **Compile Information:** Bring together all the details, descriptions, user stories, and other data into a comprehensive document.
- **Include Visual Aids if Needed:** Diagrams or charts can help convey complex ideas.
- **Review and Revise:** Make sure everything is consistent and clear. This document will be a key reference throughout the project, so it should be as accurate as possible.

### G. Obtain Stakeholder Feedback

- **Share with Stakeholders:** If possible, share the document with anyone who has a vested interest in the project (e.g., potential users, mentors).
- **Incorporate Feedback:** Make adjustments based on the feedback received.