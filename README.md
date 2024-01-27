# First_Solidity_Homework

# Example Smart Contract

Bu repo, Ethereum ağı üzerinde çalışan bir akıllı sözleşmeyi içerir. Bu sözleşme, bir sayaç ve bu sayaça ait bir açıklama içerir. Aşağıda, sözleşmenin temel özelliklerinden biri olan `get_description` fonksiyonu hakkında kısa bir açıklama bulunmaktadır.

## get_description Fonksiyonu

Bu fonksiyon, akıllı sözleşmenin içinde bulunan bir yapı olan `Counter`'ın `description` alanını döndürür. Fonksiyon, dışarıdan erişilebilir (`external`) ve durumu değiştirmeyen (`view`) bir fonksiyondur.

### Fonksiyon İmzası

```solidity
function get_description() external view returns (string memory)
```

### Kullanım

Dış dünyadan bu fonksiyon çağrıldığında, sözleşmenin `counter` yapısındaki `description` alanının değeri, çağrıyı yapan tarafa döndürülür.

### Örnek Kullanım

```javascript
string memory description = exampleContract.get_description();
```

Yukarıdaki örnek, `exampleContract` adlı bir akıllı sözleşmeden `get_description` fonksiyonunu çağırarak, sözleşmenin içindeki `counter` yapısındaki açıklama değerini alır.

---

Bu README örneği, projenin temel özelliklerinden birini anlamak için kullanılabilir. Özellikle `get_description` fonksiyonunun imzası, kullanımı ve örnek kullanımını içerir. Bu tür açıklamalar, projeyi inceleyen diğer geliştiricilere veya kullanıcılara projenin nasıl kullanılacağına dair temel bilgiler sağlar.
