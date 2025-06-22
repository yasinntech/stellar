# 🏛️ PeraChain NFT – Dijital Mirasın Zinciri

PeraChain, İstanbul’un ikonik yapılarından **Pera Palas**’ın tarihi dokusunu dijitalleştiren bir **NFT koleksiyon platformudur**. Web3 teknolojisiyle kültürel mirası sahiplenmeyi ve keşfetmeyi teşvik eder.

HackPera 2025 için geliştirilmiştir.

---

## 🚀 Projenin Amacı

PeraChain, tarihî mekânların dijital koleksiyonlarını NFT formatında saklamayı ve bu koleksiyonları kullanıcıların mint etmesini sağlar. Amaç:
- Kültürel mirası Web3 ile korumak
- Kullanıcıların etkileşimli olarak NFT'leri keşfetmesi
- Pera Palas gibi simgesel yapıların hikayesini blok zincire kazımak

---

## 🎨 Özellikler

- ✅ ERC-721 tabanlı NFT kontratı (Solidity, OpenZeppelin)
- ✅ IPFS üzerinden metadata saklama (görsel + açıklama)
- ✅ React frontend arayüzü ile mintleme ve görüntüleme
- ✅ Tamamen özelleştirilebilir koleksiyon sistemi

---

## 📸 Örnek NFT Metadata

```json
{
  "name": "Pera Palas - Oda 101",
  "description": "Pera Palas'taki tarihi Oda 101'in dijital koleksiyonu.",
  "image": "ipfs://Qm.../pera101.png"
}

⚙️ Kurulum ve Çalıştırma
1. Hardhat ortamını kur
bash
Kopyala
Düzenle
git clone https://github.com/kullaniciadi/pera-chain-nft.git
cd pera-chain-nft
npm install
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost
2. Frontend'i başlat
bash
Kopyala
Düzenle
cd frontend
npm install
npm start
3. Cüzdanını bağla ve NFT mintle!
