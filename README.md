# Server Metrics 2026-03-11 17:40:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 97976.2 (27h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2471409
telemt_connections_bad_total 46088
telemt_handshake_timeouts_total 54910
telemt_upstream_connect_attempt_total 20555
telemt_upstream_connect_success_total 20543
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 20555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10080
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5210
telemt_me_reconnect_attempts_total 33474
telemt_me_reconnect_success_total 15597
telemt_me_reader_eof_total 16897
telemt_me_idle_close_by_peer_total 16897
telemt_me_route_drop_no_conn_total 920107
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2260893
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11634
telemt_desync_full_logged_total 3196
telemt_desync_suppressed_total 8438
telemt_desync_frames_bucket_total{bucket="1_2"} 2870
telemt_desync_frames_bucket_total{bucket="3_10"} 4496
telemt_desync_frames_bucket_total{bucket="gt_10"} 4268
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16331
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 15591
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 734
telemt_user_connections_total{user="hello"} 2259336
telemt_user_connections_current{user="hello"} 1254
telemt_user_octets_from_client{user="hello"} 30849215732 (28.73 GB)
telemt_user_octets_to_client{user="hello"} 639178197148 (595.28 GB)
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 98032.7 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929036
telemt_connections_bad_total 16334
telemt_handshake_timeouts_total 80516
telemt_upstream_connect_attempt_total 30767
telemt_upstream_connect_success_total 27805
telemt_upstream_connect_fail_total 2962
telemt_upstream_connect_attempts_per_request{bucket="1"} 30767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2962
telemt_me_keepalive_timeout_total 2759
telemt_me_reconnect_attempts_total 22045
telemt_me_reconnect_success_total 19938
telemt_me_reader_eof_total 21096
telemt_me_idle_close_by_peer_total 21093
telemt_me_route_drop_no_conn_total 351994
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775286
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3055
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2081
telemt_desync_frames_bucket_total{bucket="1_2"} 927
telemt_desync_frames_bucket_total{bucket="3_10"} 1098
telemt_desync_frames_bucket_total{bucket="gt_10"} 1030
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 20215
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 19915
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 777747
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 9356071290 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 219985611520 (204.88 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 98032.7 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1585894
telemt_connections_bad_total 9646
telemt_handshake_timeouts_total 127442
telemt_upstream_connect_attempt_total 25417
telemt_upstream_connect_success_total 25096
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 25417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1890
telemt_me_reconnect_attempts_total 45085
telemt_me_reconnect_success_total 19082
telemt_me_reader_eof_total 20721
telemt_me_idle_close_by_peer_total 20721
telemt_me_route_drop_no_conn_total 578437
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1387750
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3728
telemt_desync_full_logged_total 1087
telemt_desync_suppressed_total 2641
telemt_desync_frames_bucket_total{bucket="1_2"} 901
telemt_desync_frames_bucket_total{bucket="3_10"} 1417
telemt_desync_frames_bucket_total{bucket="gt_10"} 1410
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 20156
telemt_me_refill_failed_total 807
telemt_me_writer_restored_same_endpoint_total 19070
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1074
telemt_user_connections_total{user="hello"} 1387439
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 17158236005 (15.98 GB)
telemt_user_octets_to_client{user="hello"} 422057403921 (393.07 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 98033.1 (27h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1134695
telemt_connections_bad_total 77988
telemt_handshake_timeouts_total 107021
telemt_upstream_connect_attempt_total 26462
telemt_upstream_connect_success_total 26462
telemt_upstream_connect_attempts_per_request{bucket="1"} 26462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14443
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1258
telemt_me_reconnect_attempts_total 23713
telemt_me_reconnect_success_total 21573
telemt_me_reader_eof_total 22856
telemt_me_idle_close_by_peer_total 22855
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 375643
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916079
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1928
telemt_desync_full_logged_total 738
telemt_desync_suppressed_total 1190
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 567
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21868
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 21541
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 915356
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 11024549640 (10.27 GB)
telemt_user_octets_to_client{user="hello"} 278897253924 (259.74 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 2709.2 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50208
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 260
telemt_upstream_connect_attempt_total 752
telemt_upstream_connect_success_total 752
telemt_upstream_connect_attempts_per_request{bucket="1"} 752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 304
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 594
telemt_me_reconnect_success_total 590
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 15852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47149
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 104
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_me_writer_removed_unexpected_total 582
telemt_me_writer_restored_same_endpoint_total 568
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 256
telemt_user_connections_total{user="hello"} 47149
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 5777157896 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 16548844140 (15.41 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 103
```