# Sample-Simple-Modal

## 설명

우아한테크코스에서 진행한 npm 배포 연습용 패키지입니다.

## 설치

```
npm install sample-simple-modal
```

## 사용

### 간단한 예시

```javascript
import SampleSimpleModal from 'sample-simple-modal';
```

```javascript
<SampleSimpleModal trigger={<button>눌러요</button>}>
  <h1>떴냐?</h1>
</SampleSimpleModal>
```

### Props

- `trigger`: 모달을 열기 위한 React element. 전달한 trigger에 click 이벤트 발생 시 모달이 열립니다.
- `children`: 모달 내부에 들어갈 내용.