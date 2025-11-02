# level3-task7
#include <iostream>
using namespace std;

int main() {
    int eded;
    int cem = 0;

    cout << "Ededleri daxil edin (dayanmaq ucun 0 daxil edin): " << endl;

    cin >> eded; // ilk ədədi oxuyuruq
    while (eded != 0) {
        cem += eded;       // cəminə əlavə et
        cin >> eded;       // növbəti ədədi oxu
    }

    cout << "Daxil etdiyiniz ededlerin cemi: " << cem << endl;
    return 0;
}
