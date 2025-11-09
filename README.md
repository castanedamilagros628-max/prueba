"""
Programa que calcula el promedio de una lista de notas.
Autor: Lucía - Proyecto TechJunior
"""

def calcular_promedio(notas):
    """Calcula el promedio de las notas ingresadas."""
    if not notas:
        return 0
    return sum(notas) / len(notas)

if __name__ == "__main__":
    notas = [15, 14, 17, 13, 20]
    print("Promedio:", calcular_promedio(notas))
