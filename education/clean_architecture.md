education_app/
│
├── lib/
│   ├── core/
│   │   ├── constants/
│   │   │   ├── api_constants.dart
│   │   │   └── app_constants.dart
│   │   ├── errors/
│   │   │   ├── exceptions.dart
│   │   │   └── failures.dart
│   │   ├── network/
│   │   │   └── network_info.dart
│   │   ├── usecases/
│   │   │   └── usecase.dart
│   │   └── util/
│   │       ├── input_converter.dart
│   │       └── date_formatter.dart
│   │
│   ├── features/
│   │   ├── authentication/
│   │   │   ├── data/
│   │   │   │   ├── datasources/
│   │   │   │   │   ├── auth_local_data_source.dart
│   │   │   │   │   └── auth_remote_data_source.dart
│   │   │   │   ├── models/
│   │   │   │   │   └── user_model.dart
│   │   │   │   └── repositories/
│   │   │   │       └── auth_repository_impl.dart
│   │   │   ├── domain/
│   │   │   │   ├── entities/
│   │   │   │   │   └── user.dart
│   │   │   │   ├── repositories/
│   │   │   │   │   └── auth_repository.dart
│   │   │   │   └── usecases/
│   │   │   │       ├── sign_in.dart
│   │   │   │       └── sign_up.dart
│   │   │   └── presentation/
│   │   │       ├── bloc/
│   │   │       │   ├── auth_bloc.dart
│   │   │       │   ├── auth_event.dart
│   │   │       │   └── auth_state.dart
│   │   │       ├── pages/
│   │   │       │   ├── login_page.dart
│   │   │       │   └── signup_page.dart
│   │   │       └── widgets/
│   │   │           ├── login_form.dart
│   │   │           └── signup_form.dart
│   │   │
│   │   ├── courses/
│   │   │   ├── data/
│   │   │   │   ├── datasources/
│   │   │   │   │   ├── course_local_data_source.dart
│   │   │   │   │   └── course_remote_data_source.dart
│   │   │   │   ├── models/
│   │   │   │   │   └── course_model.dart
│   │   │   │   └── repositories/
│   │   │   │       └── course_repository_impl.dart
│   │   │   ├── domain/
│   │   │   │   ├── entities/
│   │   │   │   │   └── course.dart
│   │   │   │   ├── repositories/
│   │   │   │   │   └── course_repository.dart
│   │   │   │   └── usecases/
│   │   │   │       ├── get_all_courses.dart
│   │   │   │       └── enroll_in_course.dart
│   │   │   └── presentation/
│   │   │       ├── bloc/
│   │   │       │   ├── course_bloc.dart
│   │   │       │   ├── course_event.dart
│   │   │       │   └── course_state.dart
│   │   │       ├── pages/
│   │   │       │   ├── course_list_page.dart
│   │   │       │   └── course_detail_page.dart
│   │   │       └── widgets/
│   │   │           ├── course_card.dart
│   │   │           └── course_progress_bar.dart
│   │   │
│   │   └── profile/
│   │       ├── data/
│   │       │   ├── datasources/
│   │       │   │   ├── profile_local_data_source.dart
│   │       │   │   └── profile_remote_data_source.dart
│   │       │   ├── models/
│   │       │   │   └── profile_model.dart
│   │       │   └── repositories/
│   │       │       └── profile_repository_impl.dart
│   │       ├── domain/
│   │       │   ├── entities/
│   │       │   │   └── profile.dart
│   │       │   ├── repositories/
│   │       │   │   └── profile_repository.dart
│   │       │   └── usecases/
│   │       │       ├── get_profile.dart
│   │       │       └── update_profile.dart
│   │       └── presentation/
│   │           ├── bloc/
│   │           │   ├── profile_bloc.dart
│   │           │   ├── profile_event.dart
│   │           │   └── profile_state.dart
│   │           ├── pages/
│   │           │   └── profile_page.dart
│   │           └── widgets/
│   │               └── profile_form.dart
│   │
│   ├── injection_container.dart
│   └── main.dart
│
├── test/
│   ├── core/
│   │   └── network/
│   │       └── network_info_test.dart
│   └── features/
│       ├── authentication/
│       │   ├── data/
│       │   │   ├── datasources/
│       │   │   │   ├── auth_local_data_source_test.dart
│       │   │   │   └── auth_remote_data_source_test.dart
│       │   │   ├── models/
│       │   │   │   └── user_model_test.dart
│       │   │   └── repositories/
│       │   │       └── auth_repository_impl_test.dart
│       │   ├── domain/
│       │   │   └── usecases/
│       │   │       ├── sign_in_test.dart
│       │   │       └── sign_up_test.dart
│       │   └── presentation/
│       │       └── bloc/
│       │           └── auth_bloc_test.dart
│       ├── courses/
│       │   └── ...
│       └── profile/
│           └── ...
│
├── pubspec.yaml
└── README.md