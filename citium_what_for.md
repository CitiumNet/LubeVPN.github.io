---
layout: page
title: 為何用西蒂姆？
subtitle: Why use Citium?
bigimg: /img/node.jpg
googlefonts: ["Roboto Condensed"]
---

訴諸新穎性和權威性是謬誤的思維。但不幸地，常規的網絡安全一直專注於由自詡的專家和看似值得信賴的管理機構所兜售的更新穎技術。這些技術都屢屢令人失望，歷來有被詳盡記載和被檢討，例如[瑞士Crypto公司的安全漏洞機器](https://en.wikipedia.org/wiki/Crypto_AG#Compromised_machines)、[Skype的竊聽後門](https://en.wikipedia.org/wiki/Skype_security#Eavesdropping_by_design)和[其他臭名昭著的數據洩露](https://en.wikipedia.org/wiki/List_of_data_breaches)。

西蒂姆（Citium）與常規的網絡安全辦法形成了鮮明的對比。西蒂姆（Citium）「單個權益持份者」（單個用戶節點或單個服務節點）本質上都是邪惡的。單個權益持份者把持任何的權力都可能對某些人產生不利影響。幸運的是，現代密碼學技術賦予了密碼系統設計者空間施展，他們可以剝奪傳統意義上的利益相關者所擁有的權力，如授權權、持有用戶的賬戶ID、密碼和個人信息等，而不影響密碼系統的整體可用性。

西蒂姆（Citium）充分利用了這些久經考驗的技術，創製了一個免費的、開源代碼的、完全去中心化的、[無需准入許可的區塊鏈系統](https://en.wikipedia.org/wiki/Blockchain#Permissionless)，並採用了密碼學上堅不可摧的信息安全机制，例如 __混合加密系統__、__門限加密系統__、__無差別網樹多點傳送__（IMTM） 和 __分身馬甲帳號__。西蒂姆（Citium）當前的版本能兼容 __文字__、__音像__、__視像__ 和 __即時音訊__ 的數據。使用西蒂姆（Citium）建造的去中心化應用程序（dApp）能享有非凡的數據安全功能，例如 __可推诿性__，非常適合用於建造 **[OTS無記錄通訊](https://en.wikipedia.org/wiki/Off-the-Record_Messaging)即時通訊系統**（OTS-IMS）。

It is fallacious thinking to appeal to novelty and authority. But unfortunately, conventional cybersecurity has been focusing on ever fancier technologies peddled by self-proclaimed experts and seemingly trustworthy governing bodies. A laundry list of disappointments has been documented and reviewed, such as [Swiss Crypto AG's compromised machines](https://en.wikipedia.org/wiki/Crypto_AG#Compromised_machines), [Skype's eavesdropping by design](https://en.wikipedia.org/wiki/Skype_security#Eavesdropping_by_design) and [other infamous data breaches](https://en.wikipedia.org/wiki/List_of_data_breaches).

Citium is in stark contrast to the conventional approach. Citium assumes that any single stakeholder (i.e. user node & service node) is evil by nature. Whatever power a stakeholder holds may adversely affect someone. Luckily, modern cryptography technologies bestow the power on cryptosystem designers who can mutilate the power that is conventionally available to stakeholders, such as the rights to authorize, and to hold users' account ID, password, and personal information, without affecting the overall usability of the cryptosystem.

Citium takes full advantage of these time-tested proven technologies to create a free, open-source, fully decentralized, [permissionless blockchain](https://en.wikipedia.org/wiki/Blockchain#Permissionless) that features [cryptanalytically unbreakable](https://en.wikipedia.org/wiki/Information-theoretic_security) cryptosystems and InfoSec mechanisms,  such as [**Hybrid Cryptosystem**](https://en.wikipedia.org/wiki/Hybrid_cryptosystem), [threshold cryptosystem](https://en.wikipedia.org/wiki/Threshold_cryptosystem), **indiscriminate mesh-tree multicast** (IMTM), and **sockpuppetry**. Citium's current build is capable of serving **text**, **image**, **video** and **real-time voice** data. Decentralized Apps (dApps) built on Citium can enjoy extraordinary data security features, such as **deniability**, which is well-suited to build [**Off-the-Record Messaging (OTR)**](https://en.wikipedia.org/wiki/Off-the-Record_Messaging) **Instant Messenger System**.

{: .box-success}
**服務器IP地址混淆：** 服務器IP地址混淆（SIPO）是西蒂姆（Citium）的獨特功能，可以讓HTML5的內容訪問者既可以訪問到內容但無從得知其服務器的來源IP地址，不單能有效 **防止分散式阻斷服務攻擊（DDoS）**，更可以從IP地理情報層面杜絕情報收集，有效 **防止網絡服務器被拆卸和扣押**。
<br><br>
**Server IP Obfuscation:** Server IP Obfuscation (SIPO) is a unique feature of Citium. It can hide a server's originating IP address from its visitors while letting them visit HTML5-based content on the server seamlessly. Not only can SIPO effectively **prevent distributed denial-of-service (DDoS) attacks**, but it can also curtail IP intelligence gathering (e.g. geolocation lookup), effectively **preventing web server takedown and seizure**.

## 可抵賴可推诿 ✓<br>Deniability ✓

很多中心化通訊系統自稱帶有 *不可否認性* 作為訊息安全功能之一，因為他們的用戶本身目標就是希望能系統化地讓溝通對手承擔法律責任。西蒂姆（Citium）不是為這種目標而設計的，而是提供了完全相反的信息安全功能：**可推諉性**。「可推諉性」是針對[**強制披露**](https://en.wikipedia.org/wiki/Key_disclosure_law)和其後患的最後一道防線。

一些服務商，比如說Facebook，試圖提供可推諉性，但卻沒能排除他們自己的嫌疑。這裡直接引用2017年5月18日Facebook 發布的、基於他們的 Facebook Messenger[《秘密對話技術白皮書》](https://about.fb.com/news/2016/07/messenger-starts-testing-end-to-end-encryption-with-secret-conversations/)中的一段話。

> *第三方可推諉性*屬性確保了**Facebook以外的任何一方**都無法通過密碼學方法確定報告的有效性。

這意味著Facebook仍然可以自願提交或被強制、脅迫披露，更不用說數據洩露的可能性了。這是不理想的可推諉性設計方案。而在西蒂姆（Citium）環境中則提供了完全的可推諉性。任何集中的一方的信息管理人員的或中轉的電腦，如Facebook信息安全管理員或其服務器，都無法以任何形式地背離可推諉性這一點。

西蒂姆（Citium）去中心化系統協議背後的主要動機是為對話參與者提供一個可推諉的溝通網絡，同時保持對話的機密性，例如現實生活中的私人對話，或新聞採購中的記錄。 與之相反的是，某些中心化通訊系統卻輸出可以稍後用作通訊事件和參與者身份的可驗證記錄。

Many centralized communication systems claim to have *non-repudiability* as one of their infosec features because their users purposely want to systematically hold their communicating parties legally accountable. Citium does not cater to that purpose. In fact, Citium offers the complete opposite: **deniability**, which is the last line of defense against [**forced disclosure**](https://en.wikipedia.org/wiki/Key_disclosure_law) and its repercussions.

Some service providers, such as Facebook, are trying to offer deniability but they fail to rule themselves out of the picture. Here a direct quote from the [Technical Whitepaper of Messenger Secret Conversations](https://about.fb.com/news/2016/07/messenger-starts-testing-end-to-end-encryption-with-secret-conversations/) in Facebook Messenger published on May 18, 2017:

> "[T]he *third-party deniability* property ensures that **no party outside of Facebook** can cryptographically determine the validity of a report."

It implies that Facebook can still be voluntarily submitting to or be compelled by forced disclosure and coercion, not to mention the chance of data breach. This is not ideal at all. In the Citium environment, full deniability is offered. No centralized party (e.g. data administrator) or mediatory machines (e.g. Facebook's servers) can compromise deniability in any way.  

The primary motivation behind Citium decentralized system protocol is to provide a deniable communication network for the conversation participants while keeping conversations confidential, like a private conversation in real life, or off the record in journalism sourcing. This is in contrast with some other centralized communication systems that produce output which can be later used as a verifiable record of the communication event and the identities of the participants.

## SafeMail & SDTP

西蒂姆（Citium）繼承自開源項目[SafeMail](https://github.com/maikejonne/safeemail)。儘管西蒂姆（Citium）即時通訊系統項目與 SafeMail 協議完全兼容，但我們還是決定將其稱為 Citium Instant Messenger（CIM）而不是Citium Mail，因為用戶界面和實際使用感覺就像市場上的大多數即時通訊程序。

CIM和SafeMail都使用的通信機制是「安全數據傳輸協議」 [SDTP](https://en.wikiversity.org/zh-tw/SDTP)。 SDTP規定，所有形式的通信都將相同的通用通知推送給預期的接收者。收到通知後，要求預期的收件人自己檢索消息。

Citium is inherited from the open-source project [SafeMail](https://github.com/maikejonne/safeemail). Although the Citium Instant Messenger project is fully compatible with SafeMail protocol, we decide to call it Citium Instant Messenger (CIM) instead of Citium Mail because the user interface and the actual usage feel like most of the instant messengers in the marketplace.

The communication mechanism used by both CIM and SafeMail is the "Safe Data Transfer Protocol" [(Safe Data Transfer Protocol)](https://en.wikiversity.org/zh-tw/SDTP). SDTP dictates that all forms of communication push the same generic notification to the intended recipients. Once notified, the intended recipients are required to retrieve the messages on their own.

### Push & Pull（Fitch）<br>推播與拉取（撲捉）

大多數即時通訊系統都設計為將通訊信息主動推播到預期收件人的客戶端應用程序上。然而，在西蒂姆（Citium）即時通信系統（CIM）中，推送通知只限於一般的文字提醒（即"You have a new message."；中文翻譯："您有一條新消息。"），並以加密的加密文本（"密文"）的方式將消息的極微小的片斷發送給目標收件人。預期的收件人需要自己去從芸芸眾多西蒂姆（Citium）的節點（即服務節點和用戶節點）去撲捉、拉取消息，最終與其手頭上收到了的極微小的片斷重組一起，才能獲取原有的、正確的信息。

Most instant messenger systems are designed that messages are directly pushed onto the client apps of the intended recipients. However, in Citium Instant Messenger (CIM) system, push notification is limited to a generic text reminder (i.e. "You have a new message.") and a very thin slice of the message encrypted in a ciphertext being sent to the intended recipients. The intended recipients are required to actively fetch the remaining slices on their own from the sea of Citium nodes (i.e. service nodes and user nodes), and eventually, recombining with the thin slice at hand to acquire the original, correct message.

## 門限加密系統<br>Threshold Cryptography


在任何密碼系統中，將純文本訊息轉換為密文再轉換回來的最重要組成部分是密鑰。 密鑰是密碼學整體安全性的基礎，這意味著密鑰的保護也已成為重要的命題。 可以減少密鑰洩露風險的一種方法是門限加密。 門限加密學的基本思想是，在將密鑰分發給相關節點之前，將其分為 N 個份額。 為了再次生成密鑰，不需要所有共享。 相反，一個實體只能組合 K 個份額（稱為門限）來重建密鑰。 換句話說，即使將密鑰分為 N 個份額，也僅需要 K 個份額即可重建密鑰。

In any cryptographic system, the most important component of transforming plaintext messages to ciphertext and back is the key. The key is the foundation of the overall security of cryptography, which means that the protection of the key has also become an important issue. One of the methods that can reduce the risk of the key being compromised is threshold cryptography. The basic idea of threshold cryptography is that the key is divided into n shares before being distributed to the involved entities. In order to generate the key again, not all the shares are needed. Instead, an entity can combine only k shares (known as the threshold value) to reconstruct the key. In other words, even though the key is divided into n shares, only k out of shares is needed to reconstruct the key.

### 作為額外安全措施<br>As Extra Security

歷來只有具有非常有價值的秘密（例如證書頒發機構，軍隊和政府所隱藏的）才使用門限加密系統技術。西蒂姆（Citium）的門限加密方案是確保密鑰安全並防止密鑰被洩露的額外步驟。這是因為對手將需要攻擊 K 個節點以便獲得 K 個份額來生成密鑰，而不是損害一個節點則可來獲取密鑰。這使得攻擊難度大增。

Historically, only organizations with very valuable secrets, such as certificate authorities, the military, and governments made use of threshold cryptosystem technology. Threshold cryptography scheme in Citium is an advanced and extra step to securing the key and to preventing the key from being compromised. This is because an adversary will need to attack k entities in order to obtain k shares to generate the key, rather than compromising one entity to obtain the key. This makes it more difficult for an attacker.

在西蒂姆（Citium）中，不僅是密鑰，而且消息本身也與密鑰的N個共享碎片一起被分割成N個碎片。共享的密碼文本（"密文"）被無差別地、不加區分地分發到盡可能多的西蒂姆（Citium）節點（即服務節點和用戶節點）。這樣一來，所有的內容對所有節點的所有者都是良性的。任何人都不需要對分發的任何信息負責。在西蒂姆（Citium）的門限密碼系統設計是 K = N，這意味著所有的 N 個份額都要被收集和合併。這是門限密碼系統最嚴格的信息安全设置。

In Citium, not only the key, but also the message itself are divided into n slices along with the  n shares of the key. The shared ciphertexts are distributed indiscriminately to as many Citium nodes (i.e. service nodes and user nodes). In doing so, all contents are benign to the owner of all nodes. No one is needed to be held responsible for any message distributed. In the Citium's threshold cryptosystem, it is designed that k = n. It means all n shares have to be collected and combined. It is the most stringent InfoSec setting on the threshold cryptosystem.

## 資訊安全功能<br>InfoSec Features

以下是一個西蒂姆（Citium）的信息安全（有時簡稱為InfoSec）功能列表。信息安全是一種通過減輕信息風險來保護信息的應用功能實踐。 它是信息風險管理的一部分。 它通常涉及防止或至少減少未經授權/不當訪問，使用，披露、破壞、刪除/銷毀、損壞、修改、檢查、記錄或貶值的可能性，也可能涉及減少事件如果不幸發生後的不利影響，例如「__强制性披露__」 (__force disclosure__) / 「__強制性密鑰披露__」 ([__mandatory key disclosure__](https://en.wikipedia.org/wiki/Key_disclosure_law))。

Here is a list of available InfoSec features on Citium. Information security, sometimes shortened to InfoSec, is the practice of protecting information by mitigating information risks. It is part of information risk management. It typically involves preventing or at least reducing the probability of unauthorized/inappropriate access, use, disclosure, disruption, deletion/destruction, corruption, modification, inspection, recording or devaluation, although it may also involve reducing the adverse impacts of incidents (e.g. __force disclosure__ / [__mandatory key disclosure__](https://en.wikipedia.org/wiki/Key_disclosure_law)).

| :closed_lock_with_key: | 資訊安全功能<br>InfoSec | 風險與威脅<br>Risk & Threat |
|:--:|:--:|:--|
| ✓ | 無需許可<br>Permissionless | 審查<br>Censorship |
| ✓ | 機密性<br>Confidentiality | 信息洩露<br>Data Breach |
| ✓ | 完整性<br>Integrity | 篡改<br>Tampering |
| ✓ | 可用性<br>Availability | 阻斷服務攻擊<br>DDoS Attack |
| ✓ | 授權性<br>Authorization | 特權提升<br>Privilege Escalation |
| ✓ | 驗證性<br>Authentication | 欺骗<br>Spoofing |
| ✓ | 可推诿性<br>Deniability | 強制型透漏<br>Forced Disclosure |
| ✗ | 不可否認性<br>Non-Repudiation | 可否認性<br>Repudiation |

{: .box-note}
{: style="color: grey; font-size: 80%;"}
:closed_lock_with_key:: ✓ 有該功能; ✗ 無該功能
<br>
:closed_lock_with_key:: ✓ available feature; ✗ unavailable feature

### 下一章 / NEXT CHAPTER
[**可推诿性和不可否認性**](../deniability)<br>
[**Deniability & Non-Repudiation**](../deniability)
{: .myButton}
