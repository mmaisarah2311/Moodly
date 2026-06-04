# Moodly 

An interactive, client-side daily mood tracker and mental health resource application designed to help users anchor themselves, manage emotional burnout, and visualize psychological patterns. The platform operates purely on client-side state machine mechanics, ensuring real-time data persistence without heavy background database overheads.

---

## Live Demonstration & Source Code

* **Live Website Link:** [https://mmaisarah2311.github.io/Moodly/](https://mmaisarah2311.github.io/Moodly/)
* **GitHub Repository:** [https://github.com/mmaisarah2311/Moodly](https://github.com/mmaisarah2311/Moodly)

---

## Step-by-Step Instructions to Test Login & Features

### Step 1: Portal Authentication & Login Verification
1. **Open Application UI:** Launch your browser and navigate to the live deployment link: `https://mmaisarah2311.github.io/Moodly/`.
2. **Locate Credential Fields:** Find the centralized authentication card container on the landing page.
3. **Input Pre-Configured Credentials:** 
   * Type **`Masyi`** into the *Username* field input block.
   * Type **`1234`** into the *Password* field input block.
4. **Execute Authentication:** Click the **Sign In** button container. 
5. **Verify State Redirection:** Observe the client-side system check keys against `localStorage`, authorize the profile match, and immediately initialize `dashboard.html`.
6. *Alternative Registration Test:* Click **Sign Up** to toggle the panel interface view. Input a new unique username and password, then click **Register** to cache a new profile directly inside your browser storage.

---

### Step 2: System Dashboard Overview Evaluation (`image_5a99e3.png`)
1. **Verify Metric Analytics:** Locate the top main banner header reading `HELLO, MASYITAH!` confirming active profile session rendering.
2. **Check Operational Indicators:** Confirm the `Streak: 8 days` and `Total logs: 13` metrics reflect current structural states accurately.
3. **Inspect SVG Vector Line Graph:** Examine the `Mood Metrics Over Time` interactive module; ensure data points cross-reference chronological day coordinates correctly across the structural SVG canvas grid.
4. **Evaluate Distribution Meters:** Verify that the `Distribution Profile` progress loaders calculate and display the corresponding saved percentage metrics (e.g., *38%* for specific mood vectors).
5. **Inspect Dynamic History Feed:** Scroll down to look at the vertical sleep bars and chronological log nodes. Click any trace trash bin icon to trigger an array `splice()` event listener, removing that entry instantly.

---

### Step 3: Executing a Daily Clinical Check-In (`image_5a9684.png` & `image_5a9609.png`)
1. **Navigate to Data Intake Portal:** Look at the left vertical sidebar navigation layout panel and click **Daily Check-in**.
2. **Configure Core Mood Factors:** 
   * Select an emotional status indicator baseline from the **Primary Emotion Base** dropdown element (e.g., `Calm`).
   * Drag the **Emotion Intensity Rating** HTML5 range slider node to level `3`.
3. **Log Physical & Biological Factors:** 
   * Slide the **Sleep Duration (Last Night)** element handle rightward until the label element dynamically shifts to `8 Hrs`.
   * Position the **Energy Assessment** evaluation slider directly over the center value labeled `Balanced`.
   * Adjust the **Diet & Hydration Balance** metric control until it updates to show `Stable Diet`.
4. **Toggle Self-Care Monitors:** 
   * Drag the **Physical Movement / Exercise** tracking slider to the left position to toggle `No`.
   * Drag the **Medication / Vitamins Compliance** tracker tracking slider rightward to select `Yes`.
5. **Log Biological Menstruation State:** Go down to section 4 (**BIOLOGICAL CYCLE TRACKING**). Tap the layout action block button labeled `No` or `Yes (Active Cycle)` to switch active CSS classes contextually.
6. **Set Environmental Context Triggers:** 
   * Select `Routine Day / Nothing Specific` from the **Significant Event Factor** selection node.
   * Select `Spent Time in Solitude` from the **Social Engagement Context** selection menu.
   * Select `Home / Cozy Indoor Setting` inside the **Physical Environment Location** field box.
7. **Write Analytical Memo Logs:** Type specific clinical or qualitative notes inside the **Reflection Corner** text area data block.
8. **Commit Persistent Record State:** Click the prominent **Post Analytical Record** submit button card component at the upper right. The application will immediately compile the form object array, stringify the dataset, push it directly into `localStorage`, and redirect back to the central panel view.

---

### Step 4: Interacting with the Calendar Matrix (`image_5a9302.png`)
1. **Navigate to Journey Tracking Interface:** Click **Calendar** inside the left vertical sidebar element.
2. **Inspect Automatic Grid Generations:** Look at the main interface window card titled `My Mood Journey ✨` showing month boundaries for `June 2026`.
3. **Verify Historical Badges:** Observe that days `1`, `2`, `3`, and `4` display dedicated emotional emoticon overlay stickers embedded onto the calendar cells out of saved storage arrays.
4. **Verify Modular Memo Pad Retrieval:** 
   * Click on cell **4** (showing the heart emoji asset badge).
   * Observe the structural right-side grid block element title **DAILY MEMO** update instantly.
   * Verify that the template layout wipes out the placeholder text warning (`No date selected yet!`) to instead expose your exact submission timestamps, structural text categories, and custom-typed reflection paragraph text.

---

### Step 5: Utilizing Mental Health Screening Resources (`image_5a9282.png`)
1. **Navigate to Clinical Screening Hub:** Select **Resources** from the left vertical structural layout control bar.
2. **Review Emergency Warnings:** Confirm the presence of the bright orange top global layout system alert detailing crisis emergency actions (`Malaysia Emergency: 999`).
3. **Verify Standard Testing Framework Links:** 
   * Click **Take the Test 🗗** inside the **DASS-21 Test** dashboard card grid component to check out external redirect setups.
   * Click **Open Checklist >** inside the **ASRS Screening** component box container to verify evaluation checklist tool flows.
4. **Check Emergency Contact Data Nodes:** Verify that click/call integration targets for **Befrienders KL** (`03-76272929`), *MENTARI Malaysia*, and *Talian Kasih* (`15999`) trigger localized system behaviors accurately.

---

### Step 6: Reviewing System Origin Metadata (`image_5a9225.png`)
1. **Navigate to Personal Documentation Portal:** Click **About** from the global navigation sidebar view to reveal the deep structural motivation text layout.
2. **Verify Narrative Text Modules:** Inspect the interface canvas block titled **The Story Behind Moodly** authored `By Masyitah Maisarah` to complete your assessment of the platform's features, responsive UI scaling boundaries, and core design pillars.

---

## Frameworks & Libraries Used

To maximize performance, ensure instant viewport scaling across varying display bounds, and eliminate dependency bloat, the application is built entirely with native, modern browser technologies:

* **HTML5 Structure:** Provides structural layout definitions across all core portal views (`index.html`, `dashboard.html`, `calendar.html`, `check-in.html`, `resources.html`, `about.html`).
* **CSS3 Flexbox & Grid:** Powers the user interface layouts, custom fluid themes, sidebar alignment constraints, responsive structural shifts, and calendar grid blocks.
* **Vanilla JavaScript (ES6+):** Executes user authentication indexing, JSON string processing, UNIX epoch mathematical calculations, structural dynamic SVG chart building, and state transitions.
* **Boxicons Web Vector Suite (`v2.1.4` via CDN):** Delivers clean vector interface iconography layouts across all global navigation paths.
* **Google Fonts API Integration:** Implements clean font typography configurations (`Nunito`) to provide an aesthetically pleasing visual flow.
