### **Serviço "Order"**  

Gerencia pedidos recebidos do Produto Externo A, calcula o valor total e os disponibiliza ao Produto Externo B. O serviço suporta alto volume (150k-200k pedidos/dia), com foco em escalabilidade, desempenho e consistência.  

#### **Pontos-Chave**  
- **Tecnologias:** Java 17+, Spring Boot, PostgreSQL/MongoDB, Redis.  
- **Boas Práticas:** Design Patterns, TDD, código limpo e documentado (Swagger).  
- **Arquitetura:** APIs RESTful, idempotência, transações seguras.  

> **Fluxo:** Produto Externo A → Serviço "Order" → Produto Externo B.
