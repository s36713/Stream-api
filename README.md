1. Suma dla pustego zbioru wynosi 0.0 średnia z pustego zbioru wymagałaby dzielenia przez 0 co jest błędem OptionalDouble zabezpiecza to.
2.map transformuje jeden element w jeden inny element flatMap zmienia jeden element w  wiele elementów i spłaszcza je do jednego miejsca.
3.Collectors.groupingBy zwraca standardową nieposortowaną mapę aby posrtować jej elementy po wartościach i użyć limit() trzeba utworzyć nowy strumień.
Wystąpi błąd IllegalStateException. Strumienie w Javie są jednorazowego użytku.
Ponieważ strumienie w Javie są leniwe. filter i map to tylko instrukcje ale same z siebie nic nie są wstanie odpalić aby to zadziałało należy na samym końcu dopisać jakąś operację końcową
