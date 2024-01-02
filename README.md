# Update Log

**Last Update: 2024/01/02**

Add contributions and grading adjustment

### Contributions and Grading Adjustment

The score of a certain group is $S$, with the contributions of each member $\{c_1,c_2\}$ for 2-member group and $\{c_1,c_2,c_3\}$ for 3-member group, $n$ is the number of group members.

Consider $c_1\leq c_2\leq c_3$:

Then for a member $i\ (i\in[n])$ **whose contribution rate is lower than average contribution**, his/her score will be multiplied by a allocation rate $\mu$, which is the ratio of **this person's contribution rate** $c_i$ to the **average of all higher contribution rates** in the group $\textbf{s}=\{c_j\},j\in[n]\ and\ c_j>c_i$, that is: $\mu=\frac{c_i}{\text{avg}(\textbf{s})}$, then the score after adjustment is $S'=\mu S$



Tip: the detailed requirements of **presentation** will be updated after our discussion in the following weeks.

Update on 2023/12/13:

- Modify description of query parameter `SUSTech-HTTP` as **optional** in section "2. View and Download"
- Add brief requirements of presentation in section "Encryption"

Update on 2023/12/6:

- Add description of query parameters in section "2. View and Download" to fit test demo

Update on 2023/11/29:

- Add invalid cases requirement in sections "3.1 Upload" and "3.2 Delete"

Update on 2023/11/22:

- Modify score composition of each part
- Requirement of section "5. Chunked Transfer"