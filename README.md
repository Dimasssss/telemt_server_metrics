# Server Metrics 2026-03-11 07:22:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 60930.7 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221859
telemt_connections_bad_total 13654
telemt_handshake_timeouts_total 38982
telemt_upstream_connect_attempt_total 12739
telemt_upstream_connect_success_total 12730
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 12739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 716
telemt_me_reconnect_attempts_total 21333
telemt_me_reconnect_success_total 9650
telemt_me_reader_eof_total 10487
telemt_me_idle_close_by_peer_total 10487
telemt_me_route_drop_no_conn_total 450738
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1102688
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5393
telemt_desync_full_logged_total 1504
telemt_desync_suppressed_total 3889
telemt_desync_frames_bucket_total{bucket="1_2"} 1436
telemt_desync_frames_bucket_total{bucket="3_10"} 2022
telemt_desync_frames_bucket_total{bucket="gt_10"} 1935
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10110
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 9644
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 1102353
telemt_user_connections_current{user="hello"} 1162
telemt_user_octets_from_client{user="hello"} 14568176280 (13.57 GB)
telemt_user_octets_to_client{user="hello"} 326038868592 (303.65 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60987.6 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472367
telemt_connections_bad_total 6654
telemt_handshake_timeouts_total 22689
telemt_upstream_connect_attempt_total 21565
telemt_upstream_connect_success_total 18650
telemt_upstream_connect_fail_total 2915
telemt_upstream_connect_attempts_per_request{bucket="1"} 21565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2915
telemt_me_keepalive_timeout_total 2041
telemt_me_reconnect_attempts_total 13480
telemt_me_reconnect_success_total 12654
telemt_me_reader_eof_total 13384
telemt_me_idle_close_by_peer_total 13382
telemt_me_route_drop_no_conn_total 209018
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403938
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2018
telemt_desync_full_logged_total 619
telemt_desync_suppressed_total 1399
telemt_desync_frames_bucket_total{bucket="1_2"} 655
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12800
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 12632
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 406206
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 3990284682 (3.72 GB)
telemt_user_octets_to_client{user="hello"} 106740978576 (99.41 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 60987.3 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 798551
telemt_connections_bad_total 6841
telemt_handshake_timeouts_total 43243
telemt_upstream_connect_attempt_total 16505
telemt_upstream_connect_success_total 16299
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 16505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 731
telemt_me_reconnect_attempts_total 24530
telemt_me_reconnect_success_total 12175
telemt_me_reader_eof_total 13116
telemt_me_idle_close_by_peer_total 13116
telemt_me_route_drop_no_conn_total 270859
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714178
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2083
telemt_desync_full_logged_total 607
telemt_desync_suppressed_total 1476
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 760
telemt_desync_frames_bucket_total{bucket="gt_10"} 839
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 12715
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 12164
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 714980
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 8391043613 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 211342442085 (196.83 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 60987.8 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610865
telemt_connections_bad_total 57146
telemt_handshake_timeouts_total 60717
telemt_upstream_connect_attempt_total 17181
telemt_upstream_connect_success_total 17181
telemt_upstream_connect_attempts_per_request{bucket="1"} 17181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 661
telemt_me_reconnect_attempts_total 15184
telemt_me_reconnect_success_total 14135
telemt_me_reader_eof_total 15012
telemt_me_idle_close_by_peer_total 15012
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 186943
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472601
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1061
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 642
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14301
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 14113
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 472021
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 5656034576 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 129536729304 (120.64 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60987.5 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634896
telemt_connections_bad_total 5967
telemt_handshake_timeouts_total 4585
telemt_upstream_connect_attempt_total 17048
telemt_upstream_connect_success_total 16978
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 17048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 688
telemt_me_reconnect_attempts_total 17604
telemt_me_reconnect_success_total 13818
telemt_me_reader_eof_total 14601
telemt_me_idle_close_by_peer_total 14601
telemt_me_route_drop_no_conn_total 212255
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 579369
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2728
telemt_desync_full_logged_total 1030
telemt_desync_suppressed_total 1698
telemt_desync_frames_bucket_total{bucket="1_2"} 958
telemt_desync_frames_bucket_total{bucket="3_10"} 1144
telemt_desync_frames_bucket_total{bucket="gt_10"} 626
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 14113
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 13818
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 579088
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 9891979703 (9.21 GB)
telemt_user_octets_to_client{user="hello"} 212777621362 (198.16 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 98
```