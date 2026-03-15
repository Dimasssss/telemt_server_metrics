# Server Metrics 2026-03-15 16:22:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 65300.9 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2190104
telemt_connections_bad_total 129783
telemt_handshake_timeouts_total 26868
telemt_upstream_connect_attempt_total 12930
telemt_upstream_connect_success_total 12874
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 12930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6126
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14491
telemt_me_reconnect_success_total 9596
telemt_me_reader_eof_total 10256
telemt_me_idle_close_by_peer_total 10256
telemt_me_route_drop_no_conn_total 753421
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1841685
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7133
telemt_desync_full_logged_total 1967
telemt_desync_suppressed_total 5166
telemt_desync_frames_bucket_total{bucket="1_2"} 1744
telemt_desync_frames_bucket_total{bucket="3_10"} 2732
telemt_desync_frames_bucket_total{bucket="gt_10"} 2657
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9906
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9585
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 1841183
telemt_user_connections_current{user="hello"} 2510
telemt_user_octets_from_client{user="hello"} 27000703596 (25.15 GB)
telemt_user_octets_to_client{user="hello"} 704929005640 (656.52 GB)
telemt_user_unique_ips_current{user="hello"} 699
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 65301.6 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 859187
telemt_connections_bad_total 45882
telemt_handshake_timeouts_total 60338
telemt_upstream_connect_attempt_total 16484
telemt_upstream_connect_success_total 16404
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 16484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12883
telemt_me_reconnect_success_total 12779
telemt_me_reader_eof_total 13488
telemt_me_idle_close_by_peer_total 13488
telemt_me_route_drop_no_conn_total 219507
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 657589
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2102
telemt_desync_full_logged_total 709
telemt_desync_suppressed_total 1393
telemt_desync_frames_bucket_total{bucket="1_2"} 768
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 12945
telemt_me_writer_restored_same_endpoint_total 12767
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 657832
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 9126806623 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 249860590772 (232.70 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 65301.5 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1948393
telemt_connections_bad_total 48298
telemt_handshake_timeouts_total 192095
telemt_upstream_connect_attempt_total 14188
telemt_upstream_connect_success_total 14120
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 14188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 12081
telemt_me_reconnect_success_total 10813
telemt_me_reader_eof_total 11456
telemt_me_idle_close_by_peer_total 11456
telemt_me_route_drop_no_conn_total 502032
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1171120
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2899
telemt_desync_full_logged_total 1057
telemt_desync_suppressed_total 1842
telemt_desync_frames_bucket_total{bucket="1_2"} 673
telemt_desync_frames_bucket_total{bucket="3_10"} 1113
telemt_desync_frames_bucket_total{bucket="gt_10"} 1113
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11005
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10794
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 1167088
telemt_user_connections_current{user="hello"} 1313
telemt_user_octets_from_client{user="hello"} 16883391772 (15.72 GB)
telemt_user_octets_to_client{user="hello"} 421331839884 (392.40 GB)
telemt_user_unique_ips_current{user="hello"} 415
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 65301.5 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913204
telemt_connections_bad_total 78658
telemt_handshake_timeouts_total 44519
telemt_upstream_connect_attempt_total 168797
telemt_upstream_connect_success_total 168272
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 168797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 54428
telemt_me_reconnect_success_total 12926
telemt_me_reader_eof_total 14579
telemt_me_idle_close_by_peer_total 14579
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 206590
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552165
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1539
telemt_desync_full_logged_total 400
telemt_desync_suppressed_total 1139
telemt_desync_frames_bucket_total{bucket="1_2"} 393
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14355
telemt_me_refill_failed_total 1298
telemt_me_writer_restored_same_endpoint_total 12890
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1429
telemt_user_connections_total{user="hello"} 703791
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 13545257178 (12.62 GB)
telemt_user_octets_to_client{user="hello"} 250319038437 (233.13 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 65302.4 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 924424
telemt_connections_bad_total 12047
telemt_handshake_timeouts_total 20110
telemt_upstream_connect_attempt_total 14633
telemt_upstream_connect_success_total 14553
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7821
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14957
telemt_me_reconnect_success_total 11269
telemt_me_reader_eof_total 12018
telemt_me_idle_close_by_peer_total 12018
telemt_me_route_drop_no_conn_total 230710
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 762727
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2609
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 1728
telemt_desync_frames_bucket_total{bucket="1_2"} 801
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 819
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11519
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 11261
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 762770
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 9392744564 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 272661186072 (253.94 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 117
```