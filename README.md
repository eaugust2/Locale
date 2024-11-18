# Locale
Locale Travel App: High-Fidelity React Prototype Design Document
High-Fidelity Computer Prototype
Overview
The Locale Travel App is designed to provide tailored travel recommendations that prioritize safety, user preferences, and community feedback. This high-fidelity prototype focuses on creating a visually appealing, user-friendly, and responsive interface using React.js. The app adheres to industry standards and interaction design principles, ensuring accessibility and engagement.

The following components and screens are designed with scalability and user engagement in mind:

Components and Layout Overview
Header
Purpose: Navigation and branding.
Features:
Logo aligned to the left.
Navigation links for "Home," "Search," "Saved," "Profile," and "Help."
A hamburger menu for mobile responsiveness.
Consistent across all screens.
Design Principles:
Consistency: Positioned at the top across all pages.
Affordance: Links and buttons clearly indicate interactivity.
Footer
Purpose: Provide quick access to secondary navigation and essential information.
Features:
Links to Privacy Policy, Terms of Service, and Contact Us.
Social media icons for engagement.
Simplified for mobile devices.
Design Principles:
Minimalism: Keeps non-critical elements from competing with primary content.
Screens
1. Home Screen
Purpose: Welcome users and guide them to core functionalities.
Key Features:
Hero section with a banner: “Discover Your Perfect Trip.”
Quick action buttons: “Find Recommendations,” “Explore Popular Destinations.”
Dynamic carousel of curated recommendations.
Design Decisions:
Hick’s Law: Minimal options to reduce decision fatigue.
Responsive Design: Hero section scales based on screen size.
User Interaction:
Call-to-action buttons navigate users directly to the search screen.
2. Search/Filter Screen
Purpose: Let users customize their search for travel recommendations.
Key Features:
Dynamic filters:
Budget: Slider input.
Safety: Toggle for solo/family traveler safety tips.
Preferences: Dropdown menus for cultural or adventurous activities.
Search button dynamically updates results count.
Design Decisions:
Feedback: Filters dynamically update the number of available recommendations.
Fitts’s Law: Large tappable areas for sliders and toggles.
Aesthetic Usability Effect: Visual hierarchy ensures users focus on important features.
3. Results Screen
Purpose: Display search results in an intuitive and scannable format.
Key Features:
Card-based layout: Each card contains a destination image, title, rating, and action buttons for saving or sharing.
Infinite scrolling for better user engagement.
Sorting options for "Top Rated," "Budget-Friendly," and "Safety First."
Design Decisions:
Gestalt Principles: Proximity groups related information within cards.
User Control: Sorting options are easily accessible.
4. Profile Screen
Purpose: Manage user preferences, saved items, and account settings.
Key Features:
User details: Name, photo, and editable preferences.
Tabs for “Saved Trips,” “Past Journeys,” and “Settings.”
Settings tab includes privacy and notification preferences.
Design Decisions:
Recognition Over Recall: Icons and labels help users quickly identify tabs.
Responsive Tabs: Adapts into a collapsible menu on smaller screens.
5. Error Page (404)
Purpose: Handle errors gracefully.
Key Features:
Creative messaging: “Oops! We can’t find that page.”
Call-to-action button to return to the home screen.
Design Decisions:
Emotional Design: Encourages user trust by presenting errors in a friendly, non-technical manner.
Responsive Design
Mobile View:

Hamburger menu collapses navigation links.
Cards stack vertically for better scrolling experience.
Sticky navigation and footer to improve usability.
Tablet View:

Two-column layout for search results.
Larger filter controls and cards.
Desktop View:

Full-width header and grid-based results layout.
Filters displayed in a sidebar for better control.
Heuristic Evaluation
Process
Independent Evaluation:
Each team member applied three Nielsen heuristics:
Visibility of System Status: Ensuring filters provide feedback on results.
Consistency and Standards: Navigation bar and buttons are consistent across pages.
Error Prevention: Validating filter inputs to prevent errors.
Group Discussion:
Combined findings to prioritize actionable insights.
Findings and Revisions
Issue: Lack of feedback on search results updates.

Severity: 3 (Major usability problem).
Solution: Added dynamic counters showing updated recommendation counts when filters are adjusted.
Issue: Overwhelming filter options on smaller screens.

Severity: 2 (Minor usability problem).
Solution: Grouped related filters into collapsible sections.
Issue: No visual indication of an active tab on the Profile screen.

Severity: 2 (Minor usability problem).
Solution: Highlighted active tabs with a color change and underline.
Design Principles Justification
Color Palette:

Blues and greens evoke trust and calmness, aligning with the app’s goals of safety and ease.
Accent colors (yellow for call-to-action buttons) draw attention to critical actions.
Typography:

Clean sans-serif fonts improve readability.
Hierarchical sizing differentiates titles, subtitles, and body text.
Interaction Design Principles:

Feedback: Filter updates and action button responses provide immediate confirmation.
Consistency: Buttons, navigation, and layouts follow a uniform design system.
Screenshots and Flow
Annotated Screenshots: Include screenshots of:

Home Screen.
Filter Screen.
Results Screen.
Profile Screen.
Error Page.
Each screenshot will include labeled annotations to explain key design choices.
