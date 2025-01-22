# EMR DIAGRAM


```mermaid
---

---
erDiagram


hospital_cardeal{ 
    
 cnpj REAL
 endereco TEXT
 lista_departamentos TEXT
}

Enfermeiro{ 
    nome TEXT
    cpf TEXT
}

Diretor{
		nome text
		salario real
}

Departamento{
		listaFuncionarios TEXT
		Nome TEXT
		orcamento TEXT
		
}
hospital_cardeal ||--|{ Diretor: Tem_um
hospital_cardeal ||--|{ Enfermeiro: Tem_Muitos
hospital_cardeal ||--|{ Departamento: Tem_Muitos
```