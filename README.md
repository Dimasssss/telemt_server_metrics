# Server Metrics 2026-03-15 13:29:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 54877.0 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631056
telemt_connections_bad_total 94733
telemt_handshake_timeouts_total 15527
telemt_upstream_connect_attempt_total 10907
telemt_upstream_connect_success_total 10858
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 10907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 13005
telemt_me_reconnect_success_total 8119
telemt_me_reader_eof_total 8707
telemt_me_idle_close_by_peer_total 8707
telemt_me_route_drop_no_conn_total 553783
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1373876
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5092
telemt_desync_full_logged_total 1429
telemt_desync_suppressed_total 3663
telemt_desync_frames_bucket_total{bucket="1_2"} 1308
telemt_desync_frames_bucket_total{bucket="3_10"} 1978
telemt_desync_frames_bucket_total{bucket="gt_10"} 1806
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8398
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8108
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 1373525
telemt_user_connections_current{user="hello"} 2436
telemt_user_octets_from_client{user="hello"} 19154094760 (17.84 GB)
telemt_user_octets_to_client{user="hello"} 550157655744 (512.37 GB)
telemt_user_unique_ips_current{user="hello"} 692
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 54877.8 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 655933
telemt_connections_bad_total 34350
telemt_handshake_timeouts_total 46350
telemt_upstream_connect_attempt_total 14155
telemt_upstream_connect_success_total 14085
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11094
telemt_me_reconnect_success_total 11012
telemt_me_reader_eof_total 11631
telemt_me_idle_close_by_peer_total 11631
telemt_me_route_drop_no_conn_total 164662
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497836
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1933
telemt_desync_full_logged_total 666
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 723
telemt_desync_frames_bucket_total{bucket="3_10"} 702
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11143
telemt_me_writer_restored_same_endpoint_total 11000
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 498104
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 7007078295 (6.53 GB)
telemt_user_octets_to_client{user="hello"} 188539131472 (175.59 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 54877.9 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1356242
telemt_connections_bad_total 42586
telemt_handshake_timeouts_total 140634
telemt_upstream_connect_attempt_total 12163
telemt_upstream_connect_success_total 12107
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10601
telemt_me_reconnect_success_total 9351
telemt_me_reader_eof_total 9909
telemt_me_idle_close_by_peer_total 9909
telemt_me_route_drop_no_conn_total 387720
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 878955
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2247
telemt_desync_full_logged_total 822
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 851
telemt_desync_frames_bucket_total{bucket="gt_10"} 885
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9512
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9332
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 875436
telemt_user_connections_current{user="hello"} 1330
telemt_user_octets_from_client{user="hello"} 12656071360 (11.79 GB)
telemt_user_octets_to_client{user="hello"} 321074185572 (299.02 GB)
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 54877.8 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 663838
telemt_connections_bad_total 69245
telemt_handshake_timeouts_total 36321
telemt_upstream_connect_attempt_total 73578
telemt_upstream_connect_success_total 73150
telemt_upstream_connect_fail_total 428
telemt_upstream_connect_attempts_per_request{bucket="1"} 73578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 428
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 45355
telemt_me_reconnect_success_total 11771
telemt_me_reader_eof_total 13153
telemt_me_idle_close_by_peer_total 13153
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 167807
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 438251
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1157
telemt_desync_full_logged_total 292
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 473
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12931
telemt_me_refill_failed_total 1050
telemt_me_writer_restored_same_endpoint_total 11739
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1160
telemt_user_connections_total{user="hello"} 496761
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 9345235822 (8.70 GB)
telemt_user_octets_to_client{user="hello"} 171453350084 (159.68 GB)
telemt_user_msgs_from_client{user="hello"} 1103580
telemt_user_msgs_to_client{user="hello"} 3983096
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 54878.6 (15h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696182
telemt_connections_bad_total 8923
telemt_handshake_timeouts_total 14181
telemt_upstream_connect_attempt_total 12122
telemt_upstream_connect_success_total 12058
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 12991
telemt_me_reconnect_success_total 9323
telemt_me_reader_eof_total 9983
telemt_me_idle_close_by_peer_total 9983
telemt_me_route_drop_no_conn_total 173847
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 564974
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2113
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 616
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 653
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9547
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9315
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 565016
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 7151921916 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 210210129280 (195.77 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 129
```