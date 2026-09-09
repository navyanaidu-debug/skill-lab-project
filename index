/* ================================
   RESET
================================ */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

:root {
    --primary: #7357ff;
    --primary-light: #eeeaff;
    --dark: #17151f;
    --text: #272431;
    --muted: #8b8795;
    --border: #ebe9ef;
    --background: #f7f7fa;
    --white: #ffffff;
    --green: #21b77a;
    --red: #ef6b6b;
    --orange: #f39a55;
}

body {
    font-family: "Inter", sans-serif;
    background: var(--background);
    color: var(--text);
}


/* ================================
   APP
================================ */

.app {
    display: flex;
    min-height: 100vh;
}


/* ================================
   SIDEBAR
================================ */

.sidebar {
    width: 245px;
    background: #ffffff;
    border-right: 1px solid var(--border);
    padding: 25px 16px;
    display: flex;
    flex-direction: column;
    position: fixed;
    left: 0;
    top: 0;
    bottom: 0;
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 0 10px 32px;
    font-size: 18px;
    font-weight: 800;
    color: var(--dark);
}

.logo-icon {
    width: 34px;
    height: 34px;
    border-radius: 10px;
    display: grid;
    place-items: center;
    background: var(--primary);
    color: white;
    font-size: 17px;
}

.logo-highlight {
    color: var(--primary);
}

.nav-title {
    font-size: 10px;
    font-weight: 700;
    color: #aaa6b1;
    letter-spacing: 1.2px;
    padding: 0 13px 10px;
}

.second-title {
    margin-top: 27px;
}

.nav-item {
    text-decoration: none;
    color: #817d8a;
    display: flex;
    align-items: center;
    gap: 13px;
    padding: 12px 14px;
    border-radius: 9px;
    font-size: 13px;
    font-weight: 500;
    margin-bottom: 3px;
    transition: .2s;
}

.nav-item span {
    width: 18px;
    text-align: center;
    font-size: 15px;
}

.nav-item:hover {
    background: #f6f4ff;
    color: var(--primary);
}

.nav-item.active {
    background: var(--primary-light);
    color: var(--primary);
    font-weight: 700;
}


/* ================================
   SIDEBAR BOTTOM
================================ */

.sidebar-bottom {
    margin-top: auto;
}

.upgrade-box {
    background: linear-gradient(145deg, #f3efff, #faf9ff);
    border: 1px solid #e6e0ff;
    border-radius: 13px;
    padding: 15px;
    margin-bottom: 15px;
}

.upgrade-icon {
    color: var(--primary);
    margin-bottom: 8px;
}

.upgrade-box h4 {
    font-size: 12px;
    margin-bottom: 5px;
}

.upgrade-box p {
    font-size: 10px;
    color: var(--muted);
    line-height: 1.5;
}

.upgrade-box button {
    margin-top: 11px;
    border: none;
    background: var(--primary);
    color: white;
    padding: 8px 10px;
    border-radius: 7px;
    font-size: 10px;
    cursor: pointer;
}

.user {
    border-top: 1px solid var(--border);
    padding: 15px 5px 0;
    display: flex;
    align-items: center;
    gap: 9px;
}

.avatar {
    width: 32px;
    height: 32px;
    border-radius: 50%;
    display: grid;
    place-items: center;
    background: #e9e4ff;
    color: var(--primary);
    font-size: 10px;
    font-weight: 700;
}

.user strong {
    display: block;
    font-size: 11px;
}

.user small {
    font-size: 9px;
    color: var(--muted);
}

.more {
    margin-left: auto;
    color: #aaa;
}


/* ================================
   MAIN
================================ */

.main {
    margin-left: 245px;
    width: calc(100% - 245px);
    padding: 30px 34px;
}


/* ================================
   TOPBAR
================================ */

.topbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 27px;
}

.topbar h1 {
    font-size: 23px;
    letter-spacing: -.6px;
    margin-bottom: 5px;
}

.topbar p {
    color: var(--muted);
    font-size: 12px;
}

.top-actions {
    display: flex;
    align-items: center;
    gap: 9px;
}

.date-button,
.notification {
    background: white;
    border: 1px solid var(--border);
    height: 38px;
    border-radius: 8px;
    padding: 0 12px;
    color: #686471;
    font-size: 11px;
}

.date-button {
    display: flex;
    gap: 9px;
    align-items: center;
}

.notification {
    width: 38px;
    padding: 0;
}

.add-button {
    height: 38px;
    background: var(--primary);
    color: white;
    border: none;
    border-radius: 8px;
    padding: 0 15px;
    font-size: 11px;
    font-weight: 600;
    cursor: pointer;
}


/* ================================
   STAT CARDS
================================ */

.stats {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
    margin-bottom: 17px;
}

.stat-card {
    background: white;
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 18px;
}

.stat-top {
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: var(--muted);
    font-size: 11px;
}

.card-icon {
    width: 31px;
    height: 31px;
    display: grid;
    place-items: center;
    border-radius: 8px;
    font-weight: 700;
}

.card-icon.purple {
    background: #eeeaff;
    color: var(--primary);
}

.card-icon.green {
    background: #e5f8ef;
    color: var(--green);
}

.card-icon.orange {
    background: #fff0e4;
    color: var(--orange);
}

.card-icon.blue {
    background: #e7f2ff;
    color: #468be8;
}

.stat-card h2 {
    font-size: 22px;
    margin: 15px 0 10px;
    letter-spacing: -.5px;
}

.stat-bottom {
    font-size: 9px;
    display: flex;
    gap: 5px;
}

.positive span:first-child {
    color: var(--green);
    font-weight: 700;
}

.negative span:first-child {
    color: var(--red);
    font-weight: 700;
}

.stat-bottom span:last-child {
    color: #aaa6b1;
}


/* ================================
   PANELS
================================ */

.panel {
    background: white;
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px;
}

.panel-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.panel-header h3 {
    font-size: 13px;
    margin-bottom: 4px;
}

.panel-header p {
    color: var(--muted);
    font-size: 10px;
}

.panel-header select {
    border: 1px solid var(--border);
    background: white;
    padding: 8px 10px;
    border-radius: 7px;
    color: #77737e;
    font-size: 10px;
}

.panel-header a {
    color: var(--primary);
    font-size: 10px;
    text-decoration: none;
}


/* ================================
   CONTENT GRID
================================ */

.content-grid {
    display: grid;
    grid-template-columns: 1.55fr 1fr;
    gap: 17px;
    margin-bottom: 17px;
}


/* ================================
   CHART
================================ */

.chart {
    display: flex;
    height: 235px;
    margin-top: 20px;
}

.y-labels {
    width: 40px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding-bottom: 23px;
    font-size: 8px;
    color: #aaa6b1;
}

.chart-area {
    flex: 1;
    position: relative;
}

.grid-line {
    position: absolute;
    left: 0;
    right: 0;
    border-top: 1px dashed #eeeeF2;
}

.line1 { top: 0; }
.line2 { top: 20%; }
.line3 { top: 40%; }
.line4 { top: 60%; }
.line5 { top: 80%; }

.chart svg {
    position: absolute;
    width: 100%;
    height: 200px;
    left: 0;
    top: 0;
}

.chart .area {
    fill: url(#chartGradient);
}

.chart .line {
    fill: none;
    stroke: var(--primary);
    stroke-width: 3;
    vector-effect: non-scaling-stroke;
}

.months {
    position: absolute;
    left: 0;
    right: 0;
    bottom: 0;
    display: flex;
    justify-content: space-between;
    color: #aaa6b1;
    font-size: 8px;
}

.chart-legend {
    display: flex;
    gap: 18px;
    margin-left: 40px;
    font-size: 9px;
    color: var(--muted);
}

.dot {
    display: inline-block;
    width: 7px;
    height: 7px;
    border-radius: 50%;
    margin-right: 4px;
}

.purple-dot {
    background: var(--primary);
}

.green-dot {
    background: var(--green);
}


/* ================================
   AI PANEL
================================ */

.ai-panel {
    background: linear-gradient(160deg, #fbfaff, #ffffff);
    border-color: #e6e0ff;
}

.ai-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.ai-title {
    display: flex;
    align-items: center;
    gap: 10px;
}

.ai-icon {
    width: 35px;
    height: 35px;
    background: var(--primary);
    color: white;
    border-radius: 10px;
    display: grid;
    place-items: center;
}

.ai-title h3 {
    font-size: 13px;
    margin-bottom: 3px;
}

.ai-title span {
    color: var(--muted);
    font-size: 9px;
}

.online {
    color: var(--green);
    font-size: 9px;
}

.online i {
    display: inline-block;
    width: 6px;
    height: 6px;
    background: var(--green);
    border-radius: 50%;
    margin-right: 4px;
}

.ai-message {
    display: flex;
    gap: 9px;
    margin-top: 24px;
}

.bot-avatar {
    flex-shrink: 0;
    width: 27px;
    height: 27px;
    border-radius: 8px;
    background: #eeeaff;
    color: var(--primary);
    display: grid;
    place-items: center;
    font-size: 11px;
}

.message-time {
    font-size: 8px;
    color: #aaa6b1;
}

.message p {
    margin-top: 6px;
    font-size: 10px;
    line-height: 1.6;
    color: #65616d;
}

.message strong {
    color: var(--primary);
}

.insight-button {
    margin-top: 12px;
    border: 1px solid #dcd4ff;
    background: #f6f3ff;
    color: var(--primary);
    border-radius: 7px;
    padding: 8px 10px;
    font-size: 9px;
    font-weight: 600;
}

.suggestions {
    display: flex;
    gap: 6px;
    margin-top: 20px;
}

.suggestions button {
    border: 1px solid var(--border);
    background: white;
    color: #787480;
    border-radius: 7px;
    padding: 7px 8px;
    font-size: 8px;
}

.ai-input {
    margin-top: 17px;
    display: flex;
    border: 1px solid var(--border);
    border-radius: 8px;
    background: white;
    padding: 4px;
}

.ai-input input {
    flex: 1;
    border: none;
    outline: none;
    padding: 8px;
    font-size: 9px;
}

.ai-input button {
    width: 28px;
    height: 28px;
    border: none;
    border-radius: 6px;
    background: var(--primary);
    color: white;
}


/* ================================
   LOWER GRID
================================ */

.lower-grid {
    display: grid;
    grid-template-columns: 1.35fr 1fr 1fr;
    gap: 17px;
}


/* ================================
   TRANSACTIONS
================================ */

.transaction-list {
    margin-top: 16px;
}

.transaction {
    display: flex;
    align-items: center;
    padding: 10px 0;
    border-bottom: 1px solid #f2f1f4;
}

.transaction:last-child {
    border-bottom: none;
}

.merchant-icon {
    width: 34px;
    height: 34px;
    border-radius: 9px;
    display: grid;
    place-items: center;
    font-size: 14px;
    margin-right: 10px;
}

.food {
    background: #fff0e7;
}

.transport {
    background: #eaf2ff;
}

.shopping {
    background: #f1eaff;
}

.salary {
    background: #e5f8ef;
    color: var(--green);
    font-weight: bold;
}

.transaction-info {
    flex: 1;
}

.transaction-info strong {
    display: block;
    font-size: 10px;
    margin-bottom: 4px;
}

.transaction-info span {
    color: var(--muted);
    font-size: 8px;
}

.transaction-amount {
    font-size: 10px;
    font-weight: 700;
}

.expense {
    color: #3c3944;
}

.income {
    color: var(--green);
}


/* ================================
   BUDGET
================================ */

.budget-total {
    display: flex;
    align-items: flex-end;
    margin-top: 18px;
}

.budget-total span {
    display: block;
    font-size: 9px;
    color: var(--muted);
    margin-bottom: 4px;
}

.budget-total strong {
    font-size: 18px;
}

.budget-limit {
    font-size: 9px;
    color: var(--muted);
    margin-left: 5px;
    margin-bottom: 2px;
}

.progress {
    height: 7px;
    background: #f0eff3;
    border-radius: 20px;
    overflow: hidden;
    margin-top: 12px;
}

.progress div {
    height: 100%;
    border-radius: inherit;
    background: linear-gradient(90deg, var(--primary), #9a83ff);
}

.remaining {
    display: block;
    font-size: 8px;
    color: var(--green);
    margin-top: 6px;
}

.budget-category {
    margin-top: 17px;
}

.budget-row {
    display: flex;
    justify-content: space-between;
    font-size: 9px;
    margin-bottom: 6px;
}

.budget-row strong {
    color: #625e68;
}

.mini-progress {
    height: 4px;
    background: #f1f0f3;
    border-radius: 10px;
}

.mini-progress div {
    height: 100%;
    border-radius: inherit;
}

.food-progress {
    width: 78%;
    background: #f5a365;
}

.shopping-progress {
    width: 62%;
    background: #8870ef;
}

.transport-progress {
    width: 51%;
    background: #5b9bea;
}


/* ================================
   GOALS
================================ */

.plus {
    border: none;
    background: #f1efff;
    color: var(--primary);
    width: 25px;
    height: 25px;
    border-radius: 7px;
    font-size: 15px;
}

.goal {
    display: flex;
    gap: 10px;
    margin-top: 18px;
}

.goal-icon {
    width: 34px;
    height: 34px;
    border-radius: 9px;
    background: #f4f2ff;
    display: grid;
    place-items: center;
    font-size: 14px;
}

.goal-content {
    flex: 1;
}

.goal-title {
    display: flex;
    justify-content: space-between;
    font-size: 9px;
    margin-bottom: 7px;
}

.goal-title span {
    color: var(--muted);
}

.goal-progress {
    height: 5px;
    background: #efedf2;
    border-radius: 10px;
    overflow: hidden;
}

.goal-progress div {
    height: 100%;
    background: var(--primary);
    border-radius: inherit;
}

.goal-progress.green div {
    background: var(--green);
}

.goal-content small {
    color: var(--muted);
    font-size: 7px;
    display: block;
    margin-top: 5px;
}

.add-goal {
    width: 100%;
    border: 1px dashed #d9d5e0;
    background: white;
    color: var(--primary);
    padding: 8px;
    margin-top: 17px;
    border-radius: 7px;
    font-size: 9px;
}


/* ================================
   FOOTER
================================ */

footer {
    display: flex;
    justify-content: space-between;
    color: #aaa6b1;
    font-size: 8px;
    margin-top: 25px;
    padding: 0 4px;
}


/* ================================
   RESPONSIVE
================================ */

@media (max-width: 1100px) {

    .stats {
        grid-template-columns: repeat(2, 1fr);
    }

    .content-grid {
        grid-template-columns: 1fr;
    }

    .lower-grid {
        grid-template-columns: 1fr 1fr;
    }

    .transactions-panel {
        grid-column: span 2;
    }
}


@media (max-width: 800px) {

    .sidebar {
        width: 70px;
        padding: 20px 10px;
    }

    .logo span,
    .nav-title,
    .nav-item:not(.active)::after,
    .nav-item {
        font-size: 0;
    }

    .nav-item span {
        font-size: 17px;
    }

    .logo {
        padding: 0 8px 30px;
    }

    .logo-icon {
        margin: auto;
    }

    .upgrade-box,
    .user div:not(.avatar),
    .user .more {
        display: none;
    }

    .user {
        justify-content: center;
    }

    .main {
        margin-left: 70px;
        width: calc(100% - 70px);
        padding: 22px;
    }

    .topbar {
        align-items: flex-start;
        gap: 15px;
    }

    .top-actions {
        flex-wrap: wrap;
        justify-content: flex-end;
    }

    .lower-grid {
        grid-template-columns: 1fr;
    }

    .transactions-panel {
        grid-column: span 1;
    }
}


@media (max-width: 550px) {

    .stats {
        grid-template-columns: 1fr;
    }

    .topbar {
        flex-direction: column;
    }

    .top-actions {
        width: 100%;
        justify-content: flex-start;
    }

    .date-button {
        display: none;
    }

    .main {
        padding: 15px;
    }

    .lower-grid {
        grid-template-columns: 1fr;
    }

    footer {
        flex-direction: column;
        gap: 7px;
    }
}
