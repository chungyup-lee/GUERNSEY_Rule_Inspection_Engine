# BISON 룰 기반 비전 검사 엔진

**고속 산업용 머신비전 룰 검사 라이브러리**

BISON Rule Inspection Engine은 산업용 머신비전 검사 시스템을 위해 개발된
**고성능 C++ 기반 룰 검사 엔진**입니다.\
Edge, Circle, Line, Measurement, Barcode 인식 등 다양한 검사 알고리즘을
하나의 **최적화된 검사 엔진**으로 통합하여 **실시간 생산라인 검사
환경**에 적합한 성능과 안정성을 제공합니다.

본 엔진은 **Windows / Linux / Edge AI 장비(Jetson 등)** 환경에서 동일한
검사 로직을 사용할 수 있도록 설계되었습니다.

------------------------------------------------------------------------

# BISON 검사 엔진이 필요한 이유

현대 제조 공정에서는 다음과 같은 검사 시스템이 요구됩니다.

-   빠른 처리 속도
-   안정적인 장비 운영
-   다양한 장비와의 통합
-   플랫폼 확장성

BISON Rule Inspection Engine은 이러한 요구를 충족하기 위해 **모듈형 검사
엔진 구조**로 설계되었습니다.

다음과 같은 환경에 쉽게 통합할 수 있습니다.

-   PC 기반 비전 검사 장비
-   스마트팩토리 검사 시스템
-   Edge AI 비전 장비
-   자동화 생산라인 검사 장비

하나의 검사 엔진으로 **PC 기반 검사기와 Edge AI 장비를 동시에 지원**할
수 있습니다.

------------------------------------------------------------------------

# 핵심 장점

## 고속 산업용 검사 처리

최적화된 C++ 알고리즘을 기반으로 고속 생산라인에서도 안정적인 검사
성능을 제공합니다.

지원 기능

-   Edge Detection
-   Circle Detection
-   Line Detection
-   Geometry Measurement
-   Barcode Recognition

지속적으로 동작하는 **산업용 생산 환경에서도 안정적인 검사 성능**을
유지하도록 설계되었습니다.

------------------------------------------------------------------------

## 산업용 시스템 통합 구조

검사 엔진은 **DLL / 공유 라이브러리 형태**로 제공되어 다양한 비전
시스템에 쉽게 통합할 수 있습니다.

장점

-   기존 비전 시스템에 간단히 통합 가능
-   모듈화된 검사 구조
-   안정적인 산업용 운용
-   확장 가능한 검사 파이프라인

이 구조를 통해 제조사는 **기존 시스템을 변경하지 않고 검사 기능만
업그레이드**할 수 있습니다.

------------------------------------------------------------------------

## 멀티 플랫폼 지원

핵심 검사 엔진은 **C++ 기반으로 구현**되어 다양한 플랫폼에서 동일한 검사
로직을 사용할 수 있습니다.

지원 환경

  플랫폼                지원
  --------------------- ------
  Windows 비전 시스템   ✔
  Linux 비전 시스템     ✔
  Jetson Edge AI 장비   ✔

이를 통해 **PC 검사 장비와 Edge AI 장비에서 동일한 검사 알고리즘을
사용**할 수 있습니다.

------------------------------------------------------------------------

# 검사 시스템 구조

일반적인 검사 파이프라인 구조

Camera\
↓\
Image Acquisition\
↓\
Pre Processing\
↓\
**BISON Rule Inspection Engine**\
↓\
Feature Extraction\
↓\
Inspection Decision (OK / NG)\
↓\
PLC / MES / 생산 시스템

이 구조는 **자동화 생산라인에 적합한 확장형 검사 시스템**을 구축할 수
있도록 설계되었습니다.

------------------------------------------------------------------------

# 지원 검사 알고리즘

  분류                 알고리즘
  -------------------- ----------------------------------
  Edge Detection       Sobel, Canny
  Geometry Detection   Circle Detection, Line Detection
  Measurement          Distance, Angle
  Recognition          Barcode Detection
  Filtering            Threshold, Morphology

필요에 따라 다양한 검사 알고리즘을 확장하여 사용할 수 있습니다.

------------------------------------------------------------------------

# 연동 예시

``` cpp
BisonInspectEngine engine;

engine.LoadConfig("inspection_config.json");

InspectionResult result = engine.Run(image);

if(result.isOK)
{
    SendPLC_OK();
}
else
{
    SendPLC_NG();
}
```

검사 엔진은 **C++, C#, 산업용 비전 소프트웨어** 등 다양한 환경에서
사용할 수 있습니다.

------------------------------------------------------------------------

# 검사 성능

일반적인 검사 성능 (해상도 및 하드웨어에 따라 달라질 수 있음)

  검사 종류              처리 시간
  ---------------------- -------------
  Edge + Geometry 검사   약 1\~3 ms
  Barcode Detection      약 2\~5 ms
  전체 검사 파이프라인   약 5\~10 ms

고속 생산라인에서도 **실시간 검사 성능을 유지하도록 최적화**되었습니다.

------------------------------------------------------------------------

# 적용 분야

BISON Rule Inspection Engine은 다음과 같은 산업 분야에 적용할 수
있습니다.

-   자동차 부품 검사
-   스마트팩토리 검사 시스템
-   인라인 생산 검사
-   Edge AI 비전 검사 시스템
-   고속 품질 검사 장비

------------------------------------------------------------------------

# BISON Vision Platform

BISON Rule Inspection Engine은 **BISON Vision Platform**의 핵심 구성
요소입니다.

BISON 플랫폼은 다음 기술을 통합합니다.

-   Vision Inspection Software
-   AI Inspection Engine
-   Rule-Based Inspection Engine
-   Edge Vision Devices
-   Industrial Vision Systems

이를 통해 **차세대 스마트 제조 환경을 위한 고성능 자동 검사 시스템**을
제공합니다.

------------------------------------------------------------------------

# 문의

**BISON Vision Lab**

Industrial AI Vision Systems\
Smart Factory Inspection Solutions

시스템 통합 또는 협업 문의는 BISON 팀에 연락해 주세요.
