# BPMN Game Dev Process Automation


This is an engineering study that models game development processes using BPMN 2.0 standards and mathematically validates them with Automata Theory.


## Problem Statement

* To eliminate inefficiencies and irregularities in manually managed game development processes.

* To make workflows transparent and controllable.


## Methodology

* **Modeling:** All development stages were standardized with BPMN 2.0.

* **Validation:** Processes were analyzed with the $\epsilon$-NFA (epsilon-Nondeterministic Finite Automaton) model.

* **Mathematical Expression:** The regular expression of the flow was defined as $0^{*}10^{*}11^{*}0$.


## Tools Used

* **Camunda Modeler:** Executable process models.

* **Python (Graphviz):** Dynamic flowchart generation.

* **C++ (Validation):** Automata-based process validation engine.

* **Trello:** Project management and team coordination.


## Validation Output

* **Successful:** When the process is completed according to the rules, the output "string is in the language" is received.

* **Error:** In case of a logical deviation or deficiency, the warning "string is not in the language" is given.

---

**Team Management:** Mehmet Gökçe


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Oyun geliştirme süreçlerini BPMN 2.0 standartlarıyla modelleyen ve Otomata Teorisi ile matematiksel olarak doğrulayan bir mühendislik çalışmasıdır. 


## Problem Statement

* Manuel yönetilen oyun geliştirme süreçlerindeki verimsizliği ve düzensizliği gidermek. 
* İş akışlarını şeffaf ve kontrol edilebilir hale getirmek. 


## Methodology

* **Modelleme:** Tüm geliştirme aşamaları BPMN 2.0 ile standartlaştırıldı.

* **Doğrulama:** Süreçler $\epsilon$-NFA (epsilon-Nondeterministic Finite Automaton) modeliyle analiz edildi. 

* **Matematiksel İfade:** Akışın düzenli ifadesi (Regular Expression) $0^{*}10^{*}11^{*}0$ olarak tanımlandı. 


## Tools Used

* **Camunda Modeler:** Yürütülebilir süreç modelleri. 

* **Python (Graphviz):** Dinamik akış diyagramı üretimi. 

* **C++ (Validation):** Otomata tabanlı süreç doğrulama motoru. 

* **Trello:** Proje yönetimi ve ekip koordinasyonu. 


## Validation Output

* **Başarılı:** Süreç kurallara uygun tamamlandığında "string is in the language" çıktısı alınır. 

* **Hatalı:** Mantıksal bir sapma veya eksiklikte "string is not in the language" uyarısı verilir. 


---

**Takım Yönetimi:** Mehmet Gökçe
