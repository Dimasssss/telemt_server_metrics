# Server Metrics 2026-03-12 08:48:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 10164.7 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312796
telemt_connections_bad_total 1317
telemt_handshake_timeouts_total 2204
telemt_upstream_connect_attempt_total 1973
telemt_upstream_connect_success_total 1962
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 1418
telemt_me_reconnect_success_total 1408
telemt_me_reader_eof_total 1461
telemt_me_idle_close_by_peer_total 1461
telemt_me_route_drop_no_conn_total 104362
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302178
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1434
telemt_desync_full_logged_total 354
telemt_desync_suppressed_total 1080
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1418
telemt_me_writer_restored_same_endpoint_total 1395
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 302073
telemt_user_connections_current{user="hello"} 1293
telemt_user_octets_from_client{user="hello"} 4570966972 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 83612110840 (77.87 GB)
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 39785.2 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220054
telemt_connections_bad_total 2787
telemt_handshake_timeouts_total 7505
telemt_upstream_connect_attempt_total 10245
telemt_upstream_connect_success_total 10239
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 611
telemt_me_reconnect_attempts_total 8090
telemt_me_reconnect_success_total 8048
telemt_me_reader_eof_total 8553
telemt_me_idle_close_by_peer_total 8553
telemt_me_route_drop_no_conn_total 63333
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193210
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 450
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8110
telemt_me_writer_restored_same_endpoint_total 8039
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 193567
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 2908995799 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 74282136474 (69.18 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 39785.0 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619611
telemt_connections_bad_total 2881
telemt_handshake_timeouts_total 46027
telemt_upstream_connect_attempt_total 10323
telemt_upstream_connect_success_total 10318
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4514
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 523
telemt_me_reconnect_attempts_total 8025
telemt_me_reconnect_success_total 7955
telemt_me_reader_eof_total 8356
telemt_me_idle_close_by_peer_total 8356
telemt_me_route_drop_no_conn_total 125543
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361016
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1657
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 1157
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 867
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7950
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 7914
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 361285
telemt_user_connections_current{user="hello"} 739
telemt_user_octets_from_client{user="hello"} 4290518332 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 122650436157 (114.23 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 39785.4 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297711
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 19870
telemt_upstream_connect_attempt_total 10942
telemt_upstream_connect_success_total 10898
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 10942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 785
telemt_me_reconnect_attempts_total 8920
telemt_me_reconnect_success_total 8888
telemt_me_reader_eof_total 9432
telemt_me_idle_close_by_peer_total 9432
telemt_me_route_drop_no_conn_total 99827
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249127
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 469
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8943
telemt_me_writer_restored_same_endpoint_total 8867
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 248951
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 2896608776 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 86986334376 (81.01 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39785.3 (11h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331473
telemt_connections_bad_total 373
telemt_handshake_timeouts_total 2508
telemt_upstream_connect_attempt_total 13148
telemt_upstream_connect_success_total 12993
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 13147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 570
telemt_me_reconnect_attempts_total 12492
telemt_me_reconnect_success_total 10977
telemt_me_reader_eof_total 11440
telemt_me_idle_close_by_peer_total 11440
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 106194
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312896
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1291
telemt_desync_full_logged_total 432
telemt_desync_suppressed_total 859
telemt_desync_frames_bucket_total{bucket="1_2"} 357
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 11124
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 10956
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 312838
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 3318663752 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 75966566832 (70.75 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 90
```