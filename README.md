1. Suma dla pustego zbioru wynosi 0.0 średnia z pustego zbioru wymagałaby dzielenia przez 0 co jest błędem OptionalDouble zabezpiecza to.

2.map transformuje jeden element w jeden inny element flatMap zmienia jeden element w  wiele elementów i spłaszcza je do jednego miejsca.

3.Collectors.groupingBy zwraca standardową nieposortowaną mapę aby posrtować jej elementy po wartościach i użyć limit() trzeba utworzyć nowy strumień.

4.Wystąpi błąd IllegalStateException. Strumienie w Javie są jednorazowego  użytku.


