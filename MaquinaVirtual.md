# Resumo de Aula - Azure (DIO)  

---

## Benefícios da Nuvem Azure  

- **Alta Disponibilidade** → Garantia de disponibilidade dos recursos, mesmo em caso de falhas.  
- **Escalabilidade** → Ajuste de recursos conforme a demanda (pagar apenas pelo que usar).  
- **Elasticidade** → Recursos podem ser expandidos ou reduzidos automaticamente ou manualmente.  
- **Capilaridade** → Infraestrutura distribuída globalmente, garantindo funcionamento mesmo em falhas regionais.  
- **Confiabilidade** → Permite avanços tecnológicos com segurança e confiança.  
- **Segurança** → Grande parte da proteção é realizada pela Microsoft, com suporte adicional do cliente.  
- **Governança** → Monitoramento de recursos, detecção de riscos e estratégias de mitigação.  
- **Gerenciabilidade** → Controle e gerenciamento eficiente dos recursos de nuvem.  

---

## Criando uma Máquina Virtual no Azure (via Portal)  

Passo a passo para criar rapidamente uma VM Windows no **Portal do Azure**:  

1. **Acessar o Portal do Azure**  
   - Faça login em: [https://portal.azure.com](https://portal.azure.com).  

2. **Iniciar a criação da VM**  
   - Pesquise por **Máquinas Virtuais** → Clique em **Criar** → **Máquina virtual do Azure**.  

3. **Configurar a VM**  
   - Nome da VM: `myVM`  
   - Imagem: *Windows Server 2022 Datacenter – x64 Gen 2*  
   - Usuário administrador: `azureuser` (com senha segura)  

4. **Definir regras de acesso**  
   - Permitir portas selecionadas: **RDP (3389)** e **HTTP (80)**.  

5. **Finalizar criação**  
   - Clique em **Examinar + criar** → aguarde a validação → clique em **Criar**.  

6. **Conectar-se à VM**  
   - Na página da VM, clique em **Conectar > RDP**.  
   - Baixe e abra o arquivo `.rdp`, insira o usuário e senha definidos.  

7. **Excluir recursos (limpeza)**  
   - Acesse o **Grupo de Recursos**.  
   - Clique em **Excluir grupo de recursos** para remover todos os recursos relacionados.  

---

## Conclusão  

Com esses estudos, foi possível compreender os principais **benefícios da nuvem Azure** e praticar a **criação e gerenciamento de uma Máquina Virtual** no portal, reforçando a aplicação prática da teoria.  


