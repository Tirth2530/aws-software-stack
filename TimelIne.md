
---

#### ✅ `Timeline.md`
```md
# Timeline – Gantt Chart (10 Weeks)

```mermaid
gantt
    title AWS Project Timeline
    dateFormat  YYYY-MM-DD
    section Setup
    Initialize Repo & Pi Cluster      :done,  t1, 2025-05-01, 2d
    Install K3s and Connect Nodes     :active, t2, 2025-05-03, 5d
    section Development
    AWS IoT Setup                     :t3, 2025-05-08, 3d
    Job YAML and Script               :t4, 2025-05-11, 4d
    section Integration
    S3 Upload + IAM                   :t5, 2025-05-15, 3d
    CloudWatch Logs                   :t6, 2025-05-18, 3d
    section Testing
    End-to-End Testing                :t7, 2025-05-21, 4d
    section Finalizing
    Presentation and Final Report     :t8, 2025-05-25, 5d
