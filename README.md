<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Grade 9 Biology | Lesson 1: Food Chains</title>

    <style>
        * {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f7f8;
            color: #20313a;
            line-height: 1.65;
        }

        /* =========================
           HEADER
        ========================== */

        header {
            background: linear-gradient(
                135deg,
                #123b4a,
                #176b72,
                #2b8c70
            );
            color: white;
            padding: 70px 20px;
            text-align: center;
        }

        header .label {
            text-transform: uppercase;
            letter-spacing: 3px;
            font-size: 14px;
            font-weight: bold;
            opacity: 0.85;
        }

        header h1 {
            margin: 15px 0 10px;
            font-size: clamp(34px, 6vw, 58px);
        }

        header h2 {
            margin: 0;
            color: white;
            border: none;
            font-size: clamp(22px, 4vw, 32px);
        }

        header p {
            max-width: 750px;
            margin: 20px auto 0;
            font-size: 19px;
            opacity: 0.95;
        }

        /* =========================
           MAIN CONTAINER
        ========================== */

        .container {
            width: 92%;
            max-width: 1100px;
            margin: auto;
        }

        /* =========================
           INFORMATION CARDS
        ========================== */

        .info-grid {
            display: grid;
            grid-template-columns:
                repeat(auto-fit, minmax(170px, 1fr));

            gap: 16px;
            margin: -30px auto 35px;
            position: relative;
        }

        .info-card {
            background: white;
            padding: 22px;
            border-radius: 14px;
            text-align: center;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
        }

        .info-card strong {
            display: block;
            color: #176b72;
            margin-bottom: 6px;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* =========================
           SECTIONS
        ========================== */

        .section {
            background: white;
            margin: 30px 0;
            padding: 35px;
            border-radius: 18px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.06);
        }

        h2 {
            color: #176b72;
            border-bottom: 3px solid #45a875;
            padding-bottom: 9px;
            margin-top: 0;
        }

        h3 {
            color: #247b70;
            margin-top: 28px;
        }

        /* =========================
           HIGHLIGHT BOXES
        ========================== */

        .essential-question {
            background: #e9f7f1;
            border-left: 6px solid #45a875;
            padding: 24px;
            border-radius: 10px;
            font-size: 21px;
            font-weight: bold;
            margin: 20px 0;
        }

        .key-message {
            background: #fff5d9;
            border-left: 6px solid #e0a72f;
            padding: 22px;
            border-radius: 10px;
            margin: 25px 0;
        }

        .example {
            background: #edf5ff;
            border-left: 6px solid #4b82d8;
            padding: 24px;
            border-radius: 10px;
            margin: 25px 0;
            font-size: 19px;
        }

        .international-note {
            background: #f1f1f1;
            border-left: 6px solid #777;
            padding: 20px;
            border-radius: 10px;
            margin: 20px 0;
        }

        /* =========================
           TABLES
        ========================== */

        table {
            width: 100%;
            border-collapse: collapse;
            margin: 25px 0;
        }

        th {
            background: #176b72;
            color: white;
            padding: 14px;
            text-align: left;
        }

        td {
            padding: 13px;
            border: 1px solid #d8e0e3;
            vertical-align: top;
        }

        tr:nth-child(even) {
            background: #f7fafb;
        }

        /* =========================
           FOOD CHAIN VISUAL
        ========================== */

        .food-chain {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
            gap: 12px;
            margin: 30px 0;
            font-weight: bold;
        }

        .organism {
            background: #e8f5ee;
            border: 2px solid #45a875;
            padding: 15px 20px;
            border-radius: 12px;
            text-align: center;
            min-width: 120px;
        }

        .arrow {
            font-size: 28px;
            color: #176b72;
            font-weight: bold;
        }

        /* =========================
           RUBRIC
        ========================== */

        .rubric-title {
            margin-top: 35px;
        }

        /* =========================
           FINAL SUMMARY
        ========================== */

        .final-summary {
            background: linear-gradient(
                135deg,
                #123b4a,
                #176b72
            );

            color: white;
            padding: 42px;
            border-radius: 20px;
            margin: 40px 0;
        }

        .final-summary h2,
        .final-summary h3 {
            color: white;
            border-color: rgba(255,255,255,0.5);
        }

        .final-summary .key-message {
            color: #20313a;
        }

        /* =========================
           FOOTER
        ========================== */

        footer {
            background: #123b4a;
            color: white;
            text-align: center;
            padding: 35px 20px;
            margin-top: 50px;
        }

        /* =========================
           RESPONSIVE DESIGN
        ========================== */

        @media (max-width: 700px) {

            .section {
                padding: 23px;
            }

            table {
                display: block;
                overflow-x: auto;
            }

            .food-chain {
                flex-direction: column;
            }

            .arrow {
                transform: rotate(90deg);
            }
        }
    </style>
</head>


<body>


<!-- =====================================================
     01. HEADER
====================================================== -->

<header>

    <div class="container">

        <div class="label">
            International Biology Curriculum
        </div>

        <h1>Food Chains</h1>

        <h2>Energy Flow in Ecosystems</h2>

        <p>
            Grade 9 Biology — A concise international learning
            experience focused on feeding relationships,
            trophic levels, and energy transfer.
        </p>

    </div>

</header>


<main class="container">


<!-- =====================================================
     02. LESSON INFORMATION
====================================================== -->

<section class="info-grid">

    <div class="info-card">
        <strong>Subject</strong>
        Biology
    </div>

    <div class="info-card">
        <strong>Level</strong>
        Grade 9
    </div>

    <div class="info-card">
        <strong>Topic</strong>
        Food Chains
    </div>

    <div class="info-card">
        <strong>Duration</strong>
        90 minutes
    </div>

    <div class="info-card">
        <strong>Class Size</strong>
        Approximately 30
    </div>

    <div class="info-card">
        <strong>Approach</strong>
        Inquiry & Collaboration
    </div>

</section>


<!-- =====================================================
     03. LESSON CONTEXT
====================================================== -->

<section class="section">

    <h2>1. Lesson Context</h2>

    <p>
        Every ecosystem contains organisms that depend on
        one another for energy and nutrients. A food chain
        provides a simple model for understanding these
        feeding relationships.
    </p>

    <div class="essential-question">

        Essential Question:<br>

        How does energy move through an ecosystem?

    </div>

    <p>
        Students explore how energy enters an ecosystem,
        moves from one organism to another, and becomes
        increasingly limited at higher trophic levels.
    </p>

</section>


<!-- =====================================================
     04. LEARNING OBJECTIVES
====================================================== -->

<section class="section">

    <h2>2. Learning Objectives</h2>

    <p>
        By the end of the lesson, students will be able to:
    </p>

    <ul>

        <li>
            Define the concept of a food chain.
        </li>

        <li>
            Identify producers and consumers.
        </li>

        <li>
            Recognize different trophic levels.
        </li>

        <li>
            Interpret the direction of arrows in a food chain.
        </li>

        <li>
            Identify the primary source of energy in most
            ecosystems.
        </li>

        <li>
            Construct a simple food chain.
        </li>

        <li>
            Explain how energy is transferred between organisms.
        </li>

    </ul>

</section>


<!-- =====================================================
     05. PROGRAMMATIC CONTENT
====================================================== -->

<section class="section">

    <h2>3. Programmatic Content</h2>

    <h3>Key Concepts</h3>

    <ul>

        <li>Ecosystems</li>

        <li>Food chains</li>

        <li>Producers</li>

        <li>Consumers</li>

        <li>Primary consumers</li>

        <li>Secondary consumers</li>

        <li>Tertiary consumers</li>

        <li>Trophic levels</li>

        <li>Energy transfer</li>

        <li>Decomposers</li>

    </ul>


    <h3>Scientific Skills</h3>

    <ul>

        <li>Observation</li>

        <li>Classification</li>

        <li>Model construction</li>

        <li>Scientific explanation</li>

        <li>Interpretation of diagrams</li>

        <li>Communication of scientific ideas</li>

    </ul>


    <h3>Learning Dispositions</h3>

    <ul>

        <li>Curiosity</li>

        <li>Collaboration</li>

        <li>Respect for living systems</li>

        <li>Evidence-based reasoning</li>

        <li>Environmental awareness</li>

    </ul>

</section>


<!-- =====================================================
     06. METHODOLOGY
====================================================== -->

<section class="section">

    <h2>4. Teaching and Learning Methodology</h2>

    <p>
        The lesson uses a student-centred approach combining
        inquiry, visual representation, collaboration and
        formative assessment.
    </p>

    <ul>

        <li>
            <strong>Inquiry-based learning:</strong>
            students investigate how organisms are connected.
        </li>

        <li>
            <strong>Visual learning:</strong>
            students interpret and construct food-chain models.
        </li>

        <li>
            <strong>Collaborative learning:</strong>
            students work in small groups.
        </li>

        <li>
            <strong>Guided discovery:</strong>
            the teacher supports students as they develop
            explanations.
        </li>

        <li>
            <strong>Formative assessment:</strong>
            understanding is monitored throughout the lesson.
        </li>

    </ul>

</section>


<!-- =====================================================
     07. SCIENTIFIC CONTENT
====================================================== -->

<section class="section">

    <h2>5. Core Scientific Concepts</h2>

    <h3>Producer</h3>

    <p>
        A producer is an organism that makes its own food.
        Plants and algae are common examples. Most producers
        capture energy from sunlight through photosynthesis.
    </p>


    <h3>Consumer</h3>

    <p>
        A consumer obtains energy by feeding on other organisms.
    </p>


    <h3>Decomposer</h3>

    <p>
        Decomposers break down dead organic material and help
        return nutrients to the ecosystem.
    </p>


    <h3>Food Chain</h3>

    <p>
        A food chain is a simplified model showing how energy
        is transferred through feeding relationships.
    </p>


    <h3>Trophic Level</h3>

    <p>
        A trophic level describes an organism's feeding position
        within a food chain or food web.
    </p>

</section>


<!-- =====================================================
     08. FOOD CHAIN MODEL
====================================================== -->

<section class="section">

    <h2>6. Example of a Food Chain</h2>

    <div class="food-chain">

        <div class="organism">
            ☀️<br>
            Sun
        </div>

        <div class="arrow">→</div>

        <div class="organism">
            🌱<br>
            Grass
        </div>

        <div class="arrow">→</div>

        <div class="organism">
            🐇<br>
            Rabbit
        </div>

        <div class="arrow">→</div>

        <div class="organism">
            🦊<br>
            Fox
        </div>

    </div>

    <div class="example">

        <strong>Important:</strong>

        The arrow represents the direction of energy transfer.
        It points from the organism being eaten toward the
        organism that obtains the energy.

    </div>

</section>


<!-- =====================================================
     09. TROPHIC LEVELS
====================================================== -->

<section class="section">

    <h2>7. Trophic Levels</h2>

    <table>

        <thead>

            <tr>
                <th>Level</th>
                <th>Role</th>
                <th>Example</th>
            </tr>

        </thead>

        <tbody>

            <tr>
                <td>1</td>
                <td>Producer</td>
                <td>Grass</td>
            </tr>

            <tr>
                <td>2</td>
                <td>Primary Consumer</td>
                <td>Rabbit</td>
            </tr>

            <tr>
                <td>3</td>
                <td>Secondary Consumer</td>
                <td>Fox</td>
            </tr>

            <tr>
                <td>4</td>
                <td>Tertiary Consumer</td>
                <td>Hawk</td>
            </tr>

        </tbody>

    </table>

    <div class="key-message">

        <strong>Key Idea:</strong>

        <p>
            Energy available to organisms generally decreases
            as it moves through higher trophic levels.
        </p>

    </div>

</section>


<!-- =====================================================
     10. LESSON SEQUENCE
====================================================== -->

<section class="section">

    <h2>8. 90-Minute Learning Sequence</h2>

    <table>

        <thead>

            <tr>
                <th>Stage</th>
                <th>Time</th>
                <th>Learning Activity</th>
            </tr>

        </thead>

        <tbody>

            <tr>

                <td>Engage</td>

                <td>10 min</td>

                <td>
                    Students discuss familiar examples of
                    animals eating plants or other animals.
                </td>

            </tr>

            <tr>

                <td>Explore</td>

                <td>15 min</td>

                <td>
                    Students analyse a simple food-chain model
                    and identify relationships.
                </td>

            </tr>

            <tr>

                <td>Explain</td>

                <td>20 min</td>

                <td>
                    The teacher introduces producers,
                    consumers and trophic levels.
                </td>

            </tr>

            <tr>

                <td>Practice</td>

                <td>15 min</td>

                <td>
                    Students construct a food chain with guidance.
                </td>

            </tr>

            <tr>

                <td>Collaborate</td>

                <td>20 min</td>

                <td>
                    Small groups create and explain their own
                    ecosystem food chain.
                </td>

            </tr>

            <tr>

                <td>Reflect</td>

                <td>10 min</td>

                <td>
                    Students complete an exit ticket and summarize
                    the main concept.
                </td>

            </tr>

        </tbody>

    </table>

</section>


<!-- =====================================================
     11. COLLABORATIVE ACTIVITY
====================================================== -->

<section class="section">

    <h2>9. Collaborative Learning Activity</h2>

    <p>
        Divide approximately 30 students into six groups
        of about five students.
    </p>

    <h3>Group Task</h3>

    <ol>

        <li>
            Select an ecosystem.
        </li>

        <li>
            Identify at least one producer.
        </li>

        <li>
            Identify several consumers.
        </li>

        <li>
            Arrange the organisms according to feeding relationships.
        </li>

        <li>
            Add arrows showing energy transfer.
        </li>

        <li>
            Identify the trophic level of each organism.
        </li>

        <li>
            Present and explain the food chain to the class.
        </li>

    </ol>

</section>


<!-- =====================================================
     12. ASSESSMENT
====================================================== -->

<section class="section">

    <h2>10. Assessment and Evidence of Learning</h2>

    <h3>Formative Assessment</h3>

    <ul>

        <li>
            Teacher questioning during discussion.
        </li>

        <li>
            Identification of producers and consumers.
        </li>

        <li>
            Interpretation of food-chain arrows.
        </li>

        <li>
            Group food-chain construction.
        </li>

        <li>
            Student explanations.
        </li>

    </ul>


    <h3>Exit Ticket</h3>

    <ol>

        <li>
            What is a food chain?
        </li>

        <li>
            What is a producer?
        </li>

        <li>
            What do the arrows represent?
        </li>

        <li>
            Give one example of a food chain.
        </li>

        <li>
            What is the primary energy source for most ecosystems?
        </li>

    </ol>

</section>


<!-- =====================================================
     13. RUBRIC
====================================================== -->

<section class="section">

    <h2>11. Assessment Rubric</h2>

    <table>

        <thead>

            <tr>

                <th>Criterion</th>
                <th>Beginning</th>
                <th>Developing</th>
                <th>Proficient</th>
                <th>Advanced</th>

            </tr>

        </thead>

        <tbody>

            <tr>

                <td>
                    Understanding of food chains
                </td>

                <td>
                    Shows limited understanding.
                </td>

                <td>
                    Gives a partially correct explanation.
                </td>

                <td>
                    Clearly explains the concept.
                </td>

                <td>
                    Explains the concept and its ecological significance.
                </td>

            </tr>

            <tr>

                <td>
                    Trophic levels
                </td>

                <td>
                    Identifies few levels correctly.
                </td>

                <td>
                    Identifies some levels with errors.
                </td>

                <td>
                    Correctly identifies trophic levels.
                </td>

                <td>
                    Identifies and explains trophic relationships.
                </td>

            </tr>

            <tr>

                <td>
                    Energy flow
                </td>

                <td>
                    Does not correctly identify energy direction.
                </td>

                <td>
                    Shows partial understanding.
                </td>

                <td>
                    Correctly explains energy transfer.
                </td>

                <td>
                    Provides a precise scientific explanation.
                </td>

            </tr>

            <tr>

                <td>
                    Food-chain model
                </td>

                <td>
                    Model contains major errors.
                </td>

                <td>
                    Model is completed with support.
                </td>

                <td>
                    Model is accurate and complete.
                </td>

                <td>
                    Model is accurate, clear and independently explained.
                </td>

            </tr>

            <tr>

                <td>
                    Scientific communication
                </td>

                <td>
                    Explanation is unclear.
                </td>

                <td>
                    Explanation is basic.
                </td>

                <td>
                    Explanation is clear and appropriate.
                </td>

                <td>
                    Explanation is precise and well supported.
                </td>

            </tr>

            <tr>

                <td>
                    Collaboration
                </td>

                <td>
                    Participates minimally.
                </td>

                <td>
                    Participates with support.
                </td>

                <td>
                    Contributes effectively.
                </td>

                <td>
                    Actively supports the group and peers.
                </td>

            </tr>

        </tbody>

    </table>

</section>


<!-- =====================================================
     14. FINAL INTERNATIONAL SUMMARY
====================================================== -->

<section class="final-summary">

    <h2>
        12. Final International Summary
    </h2>

    <h3>
        Food Chains: Energy Flow in Ecosystems
    </h3>

    <p>
        A food chain is a simplified model that shows how
        organisms are connected through feeding relationships
        and how energy moves through an ecosystem.
    </p>

    <p>
        Most ecosystems depend ultimately on energy from the Sun.
        Producers such as plants and algae capture this energy.
        Consumers obtain energy by feeding on producers or other
        consumers, while decomposers break down dead organic matter
        and contribute to nutrient cycling.
    </p>

    <div class="food-chain">

        <div class="organism">
            Sun
        </div>

        <div class="arrow">→</div>

        <div class="organism">
            Producer
        </div>

        <div class="arrow">→</div>

        <div class="organism">
            Primary<br>Consumer
        </div>

        <div class="arrow">→</div>

        <div class="organism">
            Secondary<br>Consumer
        </div>

    </div>

    <div class="key-message">

        <strong>Essential Takeaway</strong>

        <p>
            Energy flows through ecosystems from one trophic level
            to another. Food chains help scientists and students
            understand how organisms are connected and how changes
            in one part of an ecosystem can influence other organisms.
        </p>

    </div>

    <div class="international-note">

        <strong>International Classroom Perspective</strong>

        <p>
            The examples used in this lesson can be adapted to
            local ecosystems and biodiversity in different regions
            of the world. Students can investigate organisms
            familiar to their own environment while applying the
            same ecological concepts and scientific vocabulary.
        </p>

    </div>

</section>


</main>


<!-- =====================================================
     15. FOOTER
====================================================== -->

<footer>

    <p>
        <strong>Grade 9 Biology</strong>
    </p>

    <p>
        Lesson 1 — Food Chains and Energy Flow in Ecosystems
    </p>

    <p>
        International Educational Version
    </p>

</footer>


</body>
</html>
