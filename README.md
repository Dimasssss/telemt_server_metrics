# Server Metrics 2026-03-14 18:36:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 19143.5 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777000
telemt_connections_bad_total 39873
telemt_handshake_timeouts_total 10750
telemt_upstream_connect_attempt_total 3712
telemt_upstream_connect_success_total 3697
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 3472
telemt_me_reconnect_success_total 2671
telemt_me_reader_eof_total 2804
telemt_me_idle_close_by_peer_total 2804
telemt_me_route_drop_no_conn_total 297404
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 687601
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2368
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1688
telemt_desync_frames_bucket_total{bucket="1_2"} 565
telemt_desync_frames_bucket_total{bucket="3_10"} 890
telemt_desync_frames_bucket_total{bucket="gt_10"} 913
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2737
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 2662
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 687530
telemt_user_connections_current{user="hello"} 1917
telemt_user_octets_from_client{user="hello"} 11900878988 (11.08 GB)
telemt_user_octets_to_client{user="hello"} 225418546512 (209.94 GB)
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 19148.9 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300664
telemt_connections_bad_total 22782
telemt_handshake_timeouts_total 8972
telemt_upstream_connect_attempt_total 3980
telemt_upstream_connect_success_total 3930
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 3980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 318
telemt_me_reconnect_attempts_total 3697
telemt_me_reconnect_success_total 2905
telemt_me_reader_eof_total 3041
telemt_me_idle_close_by_peer_total 3041
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 94204
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250486
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1023
telemt_desync_full_logged_total 315
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 399
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2994
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 2889
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 250411
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 3526466452 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 90961482952 (84.71 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 19011.8 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635234
telemt_connections_bad_total 2438
telemt_handshake_timeouts_total 130521
telemt_upstream_connect_attempt_total 3759
telemt_upstream_connect_success_total 3746
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1839
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6642
telemt_me_reconnect_success_total 2736
telemt_me_reader_eof_total 2940
telemt_me_idle_close_by_peer_total 2940
telemt_me_route_drop_no_conn_total 154373
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429404
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1446
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 893
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 502
telemt_desync_frames_bucket_total{bucket="gt_10"} 752
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2883
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2703
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 429310
telemt_user_connections_current{user="hello"} 958
telemt_user_octets_from_client{user="hello"} 6412039328 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 153924663124 (143.35 GB)
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 18866.1 (5h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347387
telemt_connections_bad_total 81711
telemt_handshake_timeouts_total 43108
telemt_upstream_connect_attempt_total 4528
telemt_upstream_connect_success_total 4527
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 4484
telemt_me_reconnect_success_total 3569
telemt_me_reader_eof_total 3717
telemt_me_idle_close_by_peer_total 3717
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 76820
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217065
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 469
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 313
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3632
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3559
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 217016
telemt_user_connections_current{user="hello"} 498
telemt_user_octets_from_client{user="hello"} 3236316152 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 68172184780 (63.49 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 19161.7 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294060
telemt_connections_bad_total 1121
telemt_handshake_timeouts_total 3411
telemt_upstream_connect_attempt_total 3971
telemt_upstream_connect_success_total 3891
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 3971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 3556
telemt_me_reconnect_success_total 2887
telemt_me_reader_eof_total 3047
telemt_me_idle_close_by_peer_total 3047
telemt_me_route_drop_no_conn_total 92651
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272029
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 656
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2967
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 2869
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 272015
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 4215196260 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 118429552320 (110.30 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 89
```