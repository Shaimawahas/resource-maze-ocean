## Data Dictionary

### gameplay_events.csv
- participant_id: anonymized unique identifier
- session_id: gameplay session identifier
- level_id: maze level
- timestamp_ms: milliseconds since session start
- event_type: action performed (move, pickup, error, exit)
- event_target: object interacted with
- decision_latency_ms: time since previous action
- success_flag: correct or incorrect action

### behavioral_features.csv
Aggregated features derived from gameplay logs, including:
- exploration_entropy
- retries_after_failure
- optimal_path_ratio
- mean_decision_latency
- task_completion_ratio

### personality_labels.csv
Coarsened Big Five labels:
- openness
- conscientiousness
- extraversion
- agreeableness
- neuroticism

