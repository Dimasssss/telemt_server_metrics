# Server Metrics 2026-03-12 13:38:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 27602.8 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964369
telemt_connections_bad_total 9352
telemt_handshake_timeouts_total 9017
telemt_upstream_connect_attempt_total 5418
telemt_upstream_connect_success_total 5384
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 7872
telemt_me_reconnect_success_total 3974
telemt_me_reader_eof_total 4255
telemt_me_idle_close_by_peer_total 4254
telemt_me_route_drop_no_conn_total 339962
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917874
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4898
telemt_desync_full_logged_total 1234
telemt_desync_suppressed_total 3664
telemt_desync_frames_bucket_total{bucket="1_2"} 1226
telemt_desync_frames_bucket_total{bucket="3_10"} 1771
telemt_desync_frames_bucket_total{bucket="gt_10"} 1901
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4139
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3961
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 917688
telemt_user_connections_current{user="hello"} 1595
telemt_user_octets_from_client{user="hello"} 15386035904 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 274293970044 (255.46 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 57223.4 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466386
telemt_connections_bad_total 5305
telemt_handshake_timeouts_total 24774
telemt_upstream_connect_attempt_total 13806
telemt_upstream_connect_success_total 13799
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1111
telemt_me_reconnect_attempts_total 10820
telemt_me_reconnect_success_total 10760
telemt_me_reader_eof_total 11444
telemt_me_idle_close_by_peer_total 11444
telemt_me_route_drop_no_conn_total 134329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412787
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1405
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 582
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 345
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 10859
telemt_me_writer_restored_same_endpoint_total 10751
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 413253
telemt_user_connections_current{user="hello"} 621
telemt_user_octets_from_client{user="hello"} 6445618371 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 150745985250 (140.39 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 57223.5 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020254
telemt_connections_bad_total 5469
telemt_handshake_timeouts_total 76203
telemt_upstream_connect_attempt_total 13749
telemt_upstream_connect_success_total 13744
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 919
telemt_me_reconnect_attempts_total 10623
telemt_me_reconnect_success_total 10527
telemt_me_reader_eof_total 11090
telemt_me_idle_close_by_peer_total 11090
telemt_me_route_drop_no_conn_total 261167
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720239
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3113
telemt_desync_full_logged_total 946
telemt_desync_suppressed_total 2167
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 1122
telemt_desync_frames_bucket_total{bucket="gt_10"} 1543
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10561
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10486
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 720438
telemt_user_connections_current{user="hello"} 986
telemt_user_octets_from_client{user="hello"} 9455614772 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 234771149317 (218.65 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 57223.7 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584513
telemt_connections_bad_total 7672
telemt_handshake_timeouts_total 54042
telemt_upstream_connect_attempt_total 15250
telemt_upstream_connect_success_total 15188
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 15250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 1303
telemt_me_reconnect_attempts_total 13560
telemt_me_reconnect_success_total 12327
telemt_me_reader_eof_total 13070
telemt_me_idle_close_by_peer_total 13070
telemt_me_route_drop_no_conn_total 197054
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491752
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 995
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 283
telemt_desync_frames_bucket_total{bucket="3_10"} 409
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12459
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 12306
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 491261
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 5482114772 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 199595603568 (185.89 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57223.6 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659554
telemt_connections_bad_total 1743
telemt_handshake_timeouts_total 5389
telemt_upstream_connect_attempt_total 18152
telemt_upstream_connect_success_total 17933
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 18152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 1020
telemt_me_reconnect_attempts_total 22296
telemt_me_reconnect_success_total 15069
telemt_me_reader_eof_total 15799
telemt_me_idle_close_by_peer_total 15799
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 224468
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 613792
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2551
telemt_desync_full_logged_total 859
telemt_desync_suppressed_total 1692
telemt_desync_frames_bucket_total{bucket="1_2"} 707
telemt_desync_frames_bucket_total{bucket="3_10"} 897
telemt_desync_frames_bucket_total{bucket="gt_10"} 947
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 15443
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15040
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 613702
telemt_user_connections_current{user="hello"} 825
telemt_user_octets_from_client{user="hello"} 7094790412 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 165879663784 (154.49 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 112
```