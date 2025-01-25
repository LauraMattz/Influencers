### 📊 **Planilha de Influenciadores - Análise com Python** 🐍✨  

Bem-vindo ao repositório da análise de influenciadores! 🚀 Aqui você encontrará o código completo utilizado para analisar uma planilha de avaliações de influenciadores, aplicando técnicas de análise de dados e Machine Learning (NLP). 🧠📈  

---

## **Visão Geral**  
Este projeto foi criado para analisar avaliações de influenciadores e extrair insights a partir de uma planilha contendo:  
- **Notas (1 a 10)** atribuídas aos influenciadores.  
- **Comentários textuais** descrevendo a experiência com eles.  

📌 O objetivo foi explorar padrões nos dados, como a relação entre as notas e os sentimentos expressos nos comentários, identificar outliers e criar visualizações para facilitar a interpretação.  

---

## **Tecnologias Utilizadas**  
- **Python 3.9+** 🐍  
- **Bibliotecas**:  
  - `pandas` 📊 (manipulação de dados)  
  - `matplotlib` e `seaborn` 🎨 (visualizações gráficas)  
  - `transformers` 🤖 (análise de sentimentos com NLP)  
  - `scikit-learn` 📈 (métricas e processamento de dados)  

---

## **Principais Resultados**  

### **Distribuição de Sentimentos**  
- ✅ **Positivos:** 5.28%  
- ❌ **Negativos:** 91.99%  
- ⚖️ **Neutros:** 2.73%  

### **Distribuição de Notas**  
- 🔟 Nota **10** dominou (53.7%).  
- ❌ Nota **1** foi a segunda mais frequente (14.4%).  

### **Insights**  
- 📌 **Notas altas não refletem sentimentos positivos.** Muitos comentários negativos estavam associados a notas 10.  
- 📊 **Polarização**: Poucas notas intermediárias (2-9).  

---

## **Contribuições** 🤝  
Contribuições são bem-vindas! Para contribuir:  
1. Faça um fork do repositório.  
2. Crie um branch para sua feature ou correção:  
   ```bash
   git checkout -b minha-feature
   ```
3. Faça o commit das suas alterações:  
   ```bash
   git commit -m "Adiciona minha nova feature"
   ```
4. Envie para o repositório remoto:  
   ```bash
   git push origin minha-feature
   ```
5. Abra um pull request.  

---

## **Licença** 📝  
Este projeto está licenciado sob a [MIT License](LICENSE).
