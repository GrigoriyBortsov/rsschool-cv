Меня зовут Григорий Борцов.

мой номер телефлна:
мой телеграм:

Несмотря на возраст (мне 13 лет). Я занимаюсь прогромированием.

Я знаю С++, JS, Python, Scratch.

Вот пример на  C++

#include <iostream>

int binary_search(int arr[],int n, int target)
{
    int left = 0, right = n - 1;
    while (left <= right)
    {
        int mid = right - left / 2;
        if (mid == target)
        {
            std::cout << "inex of target is: " << mid;
            return mid;
        }
        else if(mid < target)
        {
            left = mid - 1;
        }
        else if (mid > target)
        {
            right = mid - 1;
        }
    }
    return -1;
}

int main()
{
    int a[8] = {1,3,5,8,6,5,0,3 };
    binary_search(a, 8, 12000);
}


занималься с преподователем по Python . Проходил курс по HTML & CSS.

Уровень английскогокого B2.
