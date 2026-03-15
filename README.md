# Server Metrics 2026-03-15 16:48:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 66834.2 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2272548
telemt_connections_bad_total 135654
telemt_handshake_timeouts_total 28097
telemt_upstream_connect_attempt_total 13172
telemt_upstream_connect_success_total 13115
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 13172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14646
telemt_me_reconnect_success_total 9749
telemt_me_reader_eof_total 10421
telemt_me_idle_close_by_peer_total 10421
telemt_me_route_drop_no_conn_total 784687
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1910032
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7534
telemt_desync_full_logged_total 2054
telemt_desync_suppressed_total 5480
telemt_desync_frames_bucket_total{bucket="1_2"} 1825
telemt_desync_frames_bucket_total{bucket="3_10"} 2893
telemt_desync_frames_bucket_total{bucket="gt_10"} 2816
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10063
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9738
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 314
telemt_user_connections_total{user="hello"} 1909523
telemt_user_connections_current{user="hello"} 2512
telemt_user_octets_from_client{user="hello"} 28101931644 (26.17 GB)
telemt_user_octets_to_client{user="hello"} 726625625916 (676.72 GB)
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 332
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 66835.0 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886250
telemt_connections_bad_total 47431
telemt_handshake_timeouts_total 61078
telemt_upstream_connect_attempt_total 16920
telemt_upstream_connect_success_total 16838
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 16920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7701
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 14315
telemt_me_reconnect_success_total 13121
telemt_me_reader_eof_total 13886
telemt_me_idle_close_by_peer_total 13886
telemt_me_route_drop_no_conn_total 227383
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680767
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2164
telemt_desync_full_logged_total 725
telemt_desync_suppressed_total 1439
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 808
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13328
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13109
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 681009
telemt_user_connections_current{user="hello"} 734
telemt_user_octets_from_client{user="hello"} 9785731755 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 257926500044 (240.21 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 66835.1 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2000308
telemt_connections_bad_total 48480
telemt_handshake_timeouts_total 197752
telemt_upstream_connect_attempt_total 14642
telemt_upstream_connect_success_total 14573
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 14642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12444
telemt_me_reconnect_success_total 11176
telemt_me_reader_eof_total 11839
telemt_me_idle_close_by_peer_total 11839
telemt_me_route_drop_no_conn_total 516806
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1215616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3109
telemt_desync_full_logged_total 1117
telemt_desync_suppressed_total 1992
telemt_desync_frames_bucket_total{bucket="1_2"} 721
telemt_desync_frames_bucket_total{bucket="3_10"} 1195
telemt_desync_frames_bucket_total{bucket="gt_10"} 1193
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11372
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11157
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 1211574
telemt_user_connections_current{user="hello"} 1529
telemt_user_octets_from_client{user="hello"} 17910145664 (16.68 GB)
telemt_user_octets_to_client{user="hello"} 434629770524 (404.78 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 66834.9 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 945509
telemt_connections_bad_total 80028
telemt_handshake_timeouts_total 46706
telemt_upstream_connect_attempt_total 169168
telemt_upstream_connect_success_total 168632
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 169168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 57372
telemt_me_reconnect_success_total 13198
telemt_me_reader_eof_total 14936
telemt_me_idle_close_by_peer_total 14936
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 216803
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 578531
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 43
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1650
telemt_desync_full_logged_total 430
telemt_desync_suppressed_total 1220
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 578
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14713
telemt_me_refill_failed_total 1382
telemt_me_writer_restored_same_endpoint_total 13162
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1515
telemt_user_connections_total{user="hello"} 730155
telemt_user_connections_current{user="hello"} 869
telemt_user_octets_from_client{user="hello"} 13847446926 (12.90 GB)
telemt_user_octets_to_client{user="hello"} 261412573333 (243.46 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 66835.9 (18h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959009
telemt_connections_bad_total 12055
telemt_handshake_timeouts_total 21091
telemt_upstream_connect_attempt_total 14917
telemt_upstream_connect_success_total 14836
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 14917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 15154
telemt_me_reconnect_success_total 11464
telemt_me_reader_eof_total 12227
telemt_me_idle_close_by_peer_total 12227
telemt_me_route_drop_no_conn_total 239428
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 793083
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2717
telemt_desync_full_logged_total 913
telemt_desync_suppressed_total 1804
telemt_desync_frames_bucket_total{bucket="1_2"} 842
telemt_desync_frames_bucket_total{bucket="3_10"} 1017
telemt_desync_frames_bucket_total{bucket="gt_10"} 858
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 11716
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11456
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 793127
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 9777257028 (9.11 GB)
telemt_user_octets_to_client{user="hello"} 282063604348 (262.69 GB)
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 122
```