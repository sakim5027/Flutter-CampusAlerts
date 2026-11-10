# campus_alert_app

Test | Expected handler/result | Observed result | Pass/fail/blocked | Evidence
T1   | onMessage + UI update   | onMessage shown with correct promo image | Pass | screenshot 1
T2   | onMessageOpenedApp + UI | onMessageOpenedApp with increased counter | Pass | screenshot 2
T3   | getInitialMessage + UI  | getInitialMessage with counter reset to 1 | Pass | screenshot 3
T4   | onMessage + rejection   | onMessage with increased counter and previous promo image preserved | Pass | screenshot 4
