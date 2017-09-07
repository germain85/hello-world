#include <iostream>

int main () 
{
  int ent1, ent2;
  std::cout << "Entrez un entier :" ;
  std::cin >> ent1 ;
  std::cout << "Entrez un autre entier :" ;
  std::cin >> ent2 ;
  std::cout << "Le produit de" << ent1 << "par" << ent2 << "est" << ent1*ent2 << std::endl;
  return 0;
}
