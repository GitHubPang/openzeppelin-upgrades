# Snapshot report for `src/storage-0.8.test.ts`

The actual snapshot is saved in `storage-0.8.test.ts.snap`.

Generated by [AVA](https://avajs.dev).

## user defined value types - extraction - 0.8.8

> Snapshot 1

    {
      storage: [
        {
          contract: 'Storage088',
          label: 'my_user_value',
          offset: 0,
          renamedFrom: undefined,
          retypedFrom: undefined,
          slot: '0',
          src: 'file.sol:1',
          type: 't_userDefinedValueType(MyUserValueType)3',
        },
      ],
      types: [
        [
          't_userDefinedValueType(MyUserValueType)3',
          {
            label: 'Storage088.MyUserValueType',
            members: undefined,
            numberOfBytes: '32',
          },
        ],
        [
          't_uint128',
          {
            label: 'uint128',
            members: undefined,
          },
        ],
      ],
    }

## user defined value types - extraction - 0.8.9

> Snapshot 1

    {
      storage: [
        {
          contract: 'Storage089',
          label: 'my_user_value',
          offset: 0,
          renamedFrom: undefined,
          retypedFrom: undefined,
          slot: '0',
          src: 'file.sol:1',
          type: 't_userDefinedValueType(MyUserValueType)3',
        },
      ],
      types: [
        [
          't_userDefinedValueType(MyUserValueType)3',
          {
            label: 'Storage089.MyUserValueType',
            members: undefined,
            numberOfBytes: '16',
          },
        ],
        [
          't_uint128',
          {
            label: 'uint128',
            members: undefined,
          },
        ],
      ],
    }

## user defined value types - no layout info

> Snapshot 1

    {
      storage: [
        {
          contract: 'Storage089',
          label: 'my_user_value',
          renamedFrom: undefined,
          retypedFrom: undefined,
          src: 'file.sol:1',
          type: 't_userDefinedValueType(MyUserValueType)3',
        },
      ],
      types: [
        [
          't_userDefinedValueType(MyUserValueType)3',
          {
            label: 'Storage089.MyUserValueType',
            members: undefined,
          },
        ],
        [
          't_uint128',
          {
            label: 'uint128',
            members: undefined,
          },
        ],
      ],
    }
