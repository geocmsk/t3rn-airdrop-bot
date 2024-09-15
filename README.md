# t3rn-airdrop-bot

T3rn ağında işlemleri otomatikleştirmek ve varlıklar arasında köprü kurmak için tasarlanmış bir bot, süreci sorunsuz ve verimli hale getiriyor. Artık hem Optimism Sepolia hem de Arbitrum Sepolia test ağlarını destekliyor.

## Özellikler

- t3rn ağında varlık köprüleme ve takasını otomatikleştirir.
- Özel anahtarlar içeren bir JSON dosyası aracılığıyla birden fazla cüzdanı destekler.
- Tüm işlemlerin tamamlandığından emin olmak için yeniden deneme mekanizmalarıyla sağlam hata işleme.
- Kullanıcı dostu ve kurulumu kolay.
- **Optimism Sepolia** ve **Arbitrum Sepolia**'dan köprülemeyi destekler.

## Gereksinimler

- Node.js (v14 veya üzeri)
- NPM (v6 veya üzeri)
- Kullanmayı planladığınız cüzdanlar için özel anahtarlar (`privateKeys.json` dosyasında saklanır).

## Kurulum

1. **Depoyu Klonla**:

```bash
git clone https://github.com/dante4rt/t3rn-airdrop-bot.git
cd t3rn-airdrop-bot
```

2. **Bağımlılıkları Yükle**:

```bash
npm install
```

3. **`privateKeys.json`** Oluştur:
Kök dizinde aşağıdaki biçimde `privateKeys.json` adlı bir dosya oluştur:

```json
[
"your_private_key_1",
"your_private_key_2"
]
```

4. **Botu Çalıştır**:

- Kullanılabilir menü seçeneklerini kontrol etmek için:

```bash
npm start
```

- **Arbitrum için botu çalıştırmak için Sepolia**:

```bash
npm run arbt
```

- **Optimism Sepolia** için botu çalıştırmak için:

```bash
npm run opsp
```

## Kullanım

- Kullanılabilir menü seçeneklerini kontrol etmek için `npm start` kullanın.
- Kullanmak istediğiniz ağa göre uygun komutu seçin.
- Bot, işlemleri otomatik olarak yürütecek, hataları ele alacak ve gerektiğinde yeniden deneyecektir.

## Bağışlar

Bu projenin gelişimini desteklemek isterseniz, aşağıdaki adresleri kullanarak bağış yapabilirsiniz:

- **Solana**: `GLQMG8j23ookY8Af1uLUg4CQzuQYhXcx56rkpZkyiJvP`
- **EVM**: `0x960EDa0D16f4D70df60629117ad6e5F1E13B8F44`
- **BTC**: `bc1p9za9ctgwwvc7amdng8gvrjpwhnhnwaxzj3nfv07szqwrsrudfh6qvvxrj8`

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Ayrıntılar için [LICENSE](LICENSE) dosyasına bakın.
