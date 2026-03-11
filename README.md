# Server Metrics 2026-03-11 10:56:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 73772.4 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1636192
telemt_connections_bad_total 25138
telemt_handshake_timeouts_total 42583
telemt_upstream_connect_attempt_total 15272
telemt_upstream_connect_success_total 15263
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 15272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 806
telemt_me_reconnect_attempts_total 23249
telemt_me_reconnect_success_total 11555
telemt_me_reader_eof_total 12487
telemt_me_idle_close_by_peer_total 12487
telemt_me_route_drop_no_conn_total 603105
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1487231
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7592
telemt_desync_full_logged_total 2065
telemt_desync_suppressed_total 5527
telemt_desync_frames_bucket_total{bucket="1_2"} 1977
telemt_desync_frames_bucket_total{bucket="3_10"} 2865
telemt_desync_frames_bucket_total{bucket="gt_10"} 2750
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12033
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 11549
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 1485812
telemt_user_connections_current{user="hello"} 1242
telemt_user_octets_from_client{user="hello"} 19400459296 (18.07 GB)
telemt_user_octets_to_client{user="hello"} 424826300488 (395.65 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 205
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 73829.2 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624778
telemt_connections_bad_total 10499
telemt_handshake_timeouts_total 39081
telemt_upstream_connect_attempt_total 24376
telemt_upstream_connect_success_total 21443
telemt_upstream_connect_fail_total 2933
telemt_upstream_connect_attempts_per_request{bucket="1"} 24376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2933
telemt_me_keepalive_timeout_total 2160
telemt_me_reconnect_attempts_total 15661
telemt_me_reconnect_success_total 14816
telemt_me_reader_eof_total 15684
telemt_me_idle_close_by_peer_total 15682
telemt_me_route_drop_no_conn_total 254626
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529007
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2423
telemt_desync_full_logged_total 757
telemt_desync_suppressed_total 1666
telemt_desync_frames_bucket_total{bucket="1_2"} 791
telemt_desync_frames_bucket_total{bucket="3_10"} 873
telemt_desync_frames_bucket_total{bucket="gt_10"} 759
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 14998
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14794
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 531233
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 5460476770 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 148410530864 (138.22 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 73829.1 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1083822
telemt_connections_bad_total 7732
telemt_handshake_timeouts_total 104542
telemt_upstream_connect_attempt_total 19842
telemt_upstream_connect_success_total 19598
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 19842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_timeout_total 813
telemt_me_reconnect_attempts_total 28456
telemt_me_reconnect_success_total 14834
telemt_me_reader_eof_total 15940
telemt_me_idle_close_by_peer_total 15940
telemt_me_route_drop_no_conn_total 359558
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930799
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2596
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1825
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 969
telemt_desync_frames_bucket_total{bucket="gt_10"} 1013
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15448
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 14823
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 931630
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 10928986389 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 283539115429 (264.07 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 73829.6 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788134
telemt_connections_bad_total 69408
telemt_handshake_timeouts_total 74288
telemt_upstream_connect_attempt_total 20119
telemt_upstream_connect_success_total 20119
telemt_upstream_connect_attempts_per_request{bucket="1"} 20119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 773
telemt_me_reconnect_attempts_total 17507
telemt_me_reconnect_success_total 16448
telemt_me_reader_eof_total 17456
telemt_me_idle_close_by_peer_total 17455
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 249063
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 621587
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1377
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 505
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 16644
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 16423
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 620956
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 7126451880 (6.64 GB)
telemt_user_octets_to_client{user="hello"} 177755911584 (165.55 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73829.3 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 842876
telemt_connections_bad_total 6094
telemt_handshake_timeouts_total 7942
telemt_upstream_connect_attempt_total 19879
telemt_upstream_connect_success_total 19796
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 19879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 829
telemt_me_reconnect_attempts_total 19806
telemt_me_reconnect_success_total 16009
telemt_me_reader_eof_total 16904
telemt_me_idle_close_by_peer_total 16904
telemt_me_route_drop_no_conn_total 293651
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 764786
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3160
telemt_desync_full_logged_total 1178
telemt_desync_suppressed_total 1982
telemt_desync_frames_bucket_total{bucket="1_2"} 1082
telemt_desync_frames_bucket_total{bucket="3_10"} 1268
telemt_desync_frames_bucket_total{bucket="gt_10"} 810
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16326
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 16009
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 764531
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 11556770783 (10.76 GB)
telemt_user_octets_to_client{user="hello"} 279775771630 (260.56 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 90
```