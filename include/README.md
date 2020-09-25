# Здесь размещается файл **task1.h**
#include "task1.h"

#include "gtest/gtest.h"

TEST(task1, test1) {
    ASSERT_EQ(3.0, average(4.0, 2.0));
}

TEST(task1, test2) {
    ASSERT_NEAR(1.45, average(5.40, -2.5),0.01);
}

TEST(task1, test3) {
    ASSERT_EQ(0.0, average(-50.0, 50.0));
}

TEST(task1, test4) {
    ASSERT_EQ(1.0, improve(2.0, 0.0));
}

TEST(task1, test5) {
    ASSERT_EQ(3.5, improve(5.0, 10.0));
}

TEST(task1, test6) {
    ASSERT_EQ(0.0, improve(3.0, -9.0));
}

TEST(task1, test7) {
    ASSERT_EQ(2.175, improve(2.35, 4.7));
}

TEST(task1, test8) {
    ASSERT_EQ(0.0, good(4.0, 0.0));
}

TEST(task1, test9) {
    ASSERT_EQ(0.0, good(10.0, -1.0));
}

TEST(task1, test10) {
    ASSERT_EQ(0.0, good(-32.0, 32.0));
}








