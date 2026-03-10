# Server Metrics 2026-03-10 19:25:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 17911.1 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564350
telemt_connections_bad_total 8000
telemt_handshake_timeouts_total 3861
telemt_upstream_connect_attempt_total 3583
telemt_upstream_connect_success_total 3574
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1820
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 13083
telemt_me_reconnect_success_total 2622
telemt_me_reader_eof_total 2959
telemt_me_idle_close_by_peer_total 2959
telemt_me_route_drop_no_conn_total 235124
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533058
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2826
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 1088
telemt_desync_frames_bucket_total{bucket="gt_10"} 986
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2961
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2616
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 532962
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 7918723200 (7.37 GB)
telemt_user_octets_to_client{user="hello"} 154427185464 (143.82 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 17967.9 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244255
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 16517
telemt_upstream_connect_attempt_total 8881
telemt_upstream_connect_success_total 6137
telemt_upstream_connect_fail_total 2744
telemt_upstream_connect_attempts_per_request{bucket="1"} 8881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2014
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1881
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2744
telemt_me_keepalive_timeout_total 709
telemt_me_reconnect_attempts_total 4009
telemt_me_reconnect_success_total 3224
telemt_me_reader_eof_total 3370
telemt_me_idle_close_by_peer_total 3368
telemt_me_route_drop_no_conn_total 131852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207200
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 980
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 706
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3284
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 3203
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 209159
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 2219903626 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 50629641422 (47.15 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 17967.8 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405333
telemt_connections_bad_total 1333
telemt_handshake_timeouts_total 32150
telemt_upstream_connect_attempt_total 5456
telemt_upstream_connect_success_total 5373
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 5456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 6838
telemt_me_reconnect_success_total 3389
telemt_me_reader_eof_total 3606
telemt_me_idle_close_by_peer_total 3606
telemt_me_route_drop_no_conn_total 137898
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346799
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1102
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 797
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 373
telemt_desync_frames_bucket_total{bucket="gt_10"} 464
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3557
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 3378
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 347751
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 4998291221 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 109792863033 (102.25 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 17968.2 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267669
telemt_connections_bad_total 17788
telemt_handshake_timeouts_total 23639
telemt_upstream_connect_attempt_total 4880
telemt_upstream_connect_success_total 4880
telemt_upstream_connect_attempts_per_request{bucket="1"} 4880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 4966
telemt_me_reconnect_success_total 3952
telemt_me_reader_eof_total 4129
telemt_me_idle_close_by_peer_total 4129
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 87548
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215206
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 562
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 197
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 4023
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 3939
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 214977
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 3452017360 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 62787532628 (58.48 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 17975.9 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282038
telemt_connections_bad_total 829
telemt_handshake_timeouts_total 1875
telemt_upstream_connect_attempt_total 5435
telemt_upstream_connect_success_total 5416
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 5435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 4502
telemt_me_reconnect_success_total 4468
telemt_me_reader_eof_total 4598
telemt_me_idle_close_by_peer_total 4598
telemt_me_route_drop_no_conn_total 104877
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266595
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1501
telemt_desync_full_logged_total 545
telemt_desync_suppressed_total 956
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 4532
telemt_me_writer_restored_same_endpoint_total 4468
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 266523
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 5411464588 (5.04 GB)
telemt_user_octets_to_client{user="hello"} 83742113992 (77.99 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 77
```