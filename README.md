# Docker Port Assignment Cheat Sheet 🚀

Organize your Docker container ports by category for clarity and easy management.

---

## Common Port Ranges & Categories

| Port Range  | Category               | Examples / Notes                           |
|-------------|------------------------|--------------------------------------------|
| 3000–3099   | Development            | Web apps, dev servers, testing environments |
| 3100–3199   | Networking             | Proxies, VPNs, load balancers               |
| 3200–3299   | Monitoring & Logging   | Tools like Netdata, Prometheus, ELK stack  |
| 3300–3399   | Databases              | MySQL, PostgreSQL, MongoDB                   |
| 3400–3499   | Caching & Queues       | Redis, RabbitMQ, Memcached                   |
| 3500–3599   | CI/CD & Automation     | Jenkins, GitLab Runner, Drone                |
| 3600–3699   | Messaging & Communication | MQTT brokers, chat servers, email servers  |
| 3700–3799   | Media & Streaming      | Plex, Jellyfin, streaming services           |
| 3800–3899   | Security & Authentication | OAuth servers, LDAP, Vault                   |
| 3900–3999   | Misc / Custom          | Custom apps or less common services          |

---

## Popular Specific Ports

| Port  | Service                   | Common Use Case                   |
|-------|---------------------------|---------------------------------|
| 80    | HTTP                      | Web traffic                     |
| 443   | HTTPS                     | Secure web traffic              |
| 8080  | Alternate HTTP            | Dev servers, proxy apps         |
| 8443  | Alternate HTTPS           | Secure dev servers              |
| 9000  | Often used by monitoring  | e.g., Netdata, SonarQube        |
| 5432  | PostgreSQL default port   | Database connections            |
| 27017 | MongoDB default port      | Database connections            |

---

## Tips for Using Ports

- Always check if the port is free before assigning to avoid conflicts 🚦  
- Use `.env` files to manage port variables in your Docker Compose setups 🔧  
- Document your port assignments especially if you’re in a team 📖  
- Keep ports above 3000 for custom apps to avoid clashes with common system services ⚙️  

---

Happy Dockering! 🐳✨

---
