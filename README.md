# Server Metrics 2026-03-15 14:25:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 58250.2 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1798901
telemt_connections_bad_total 99756
telemt_handshake_timeouts_total 19942
telemt_upstream_connect_attempt_total 11622
telemt_upstream_connect_success_total 11573
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13542
telemt_me_reconnect_success_total 8652
telemt_me_reader_eof_total 9257
telemt_me_idle_close_by_peer_total 9257
telemt_me_route_drop_no_conn_total 615507
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1520349
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5720
telemt_desync_full_logged_total 1601
telemt_desync_suppressed_total 4119
telemt_desync_frames_bucket_total{bucket="1_2"} 1442
telemt_desync_frames_bucket_total{bucket="3_10"} 2213
telemt_desync_frames_bucket_total{bucket="gt_10"} 2065
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8943
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8641
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 1519963
telemt_user_connections_current{user="hello"} 2242
telemt_user_octets_from_client{user="hello"} 21672710408 (20.18 GB)
telemt_user_octets_to_client{user="hello"} 600995588236 (559.72 GB)
telemt_user_unique_ips_current{user="hello"} 662
telemt_user_unique_ips_recent_window{user="hello"} 281
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 58251.1 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731009
telemt_connections_bad_total 39596
telemt_handshake_timeouts_total 57771
telemt_upstream_connect_attempt_total 14828
telemt_upstream_connect_success_total 14756
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 14828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11590
telemt_me_reconnect_success_total 11499
telemt_me_reader_eof_total 12154
telemt_me_idle_close_by_peer_total 12154
telemt_me_route_drop_no_conn_total 181756
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549000
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1985
telemt_desync_full_logged_total 685
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 738
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11640
telemt_me_writer_restored_same_endpoint_total 11487
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 549253
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 7706338727 (7.18 GB)
telemt_user_octets_to_client{user="hello"} 206252356180 (192.09 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 58251.0 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1564848
telemt_connections_bad_total 45723
telemt_handshake_timeouts_total 161302
telemt_upstream_connect_attempt_total 12809
telemt_upstream_connect_success_total 12749
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 12809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11067
telemt_me_reconnect_success_total 9813
telemt_me_reader_eof_total 10403
telemt_me_idle_close_by_peer_total 10403
telemt_me_route_drop_no_conn_total 428360
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 969748
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2449
telemt_desync_full_logged_total 901
telemt_desync_suppressed_total 1548
telemt_desync_frames_bucket_total{bucket="1_2"} 564
telemt_desync_frames_bucket_total{bucket="3_10"} 939
telemt_desync_frames_bucket_total{bucket="gt_10"} 946
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9982
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9794
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 965854
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 13963454048 (13.00 GB)
telemt_user_octets_to_client{user="hello"} 348737145052 (324.79 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 214
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 58251.0 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753656
telemt_connections_bad_total 72070
telemt_handshake_timeouts_total 39880
telemt_upstream_connect_attempt_total 140965
telemt_upstream_connect_success_total 140489
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 140965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 50883
telemt_me_reconnect_success_total 11794
telemt_me_reader_eof_total 13347
telemt_me_idle_close_by_peer_total 13347
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 170760
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447063
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1173
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13126
telemt_me_refill_failed_total 1222
telemt_me_writer_restored_same_endpoint_total 11762
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1332
telemt_user_connections_total{user="hello"} 572710
telemt_user_connections_current{user="hello"} 1007
telemt_user_octets_from_client{user="hello"} 10584271125 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 194856093343 (181.47 GB)
telemt_user_msgs_from_client{user="hello"} 2449075
telemt_user_msgs_to_client{user="hello"} 9146732
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 58252.0 (16h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 772387
telemt_connections_bad_total 9294
telemt_handshake_timeouts_total 16049
telemt_upstream_connect_attempt_total 12827
telemt_upstream_connect_success_total 12757
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13516
telemt_me_reconnect_success_total 9841
telemt_me_reader_eof_total 10527
telemt_me_idle_close_by_peer_total 10527
telemt_me_route_drop_no_conn_total 191881
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628316
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2285
telemt_desync_full_logged_total 763
telemt_desync_suppressed_total 1522
telemt_desync_frames_bucket_total{bucket="1_2"} 682
telemt_desync_frames_bucket_total{bucket="3_10"} 888
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10070
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9833
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 628361
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 7864596532 (7.32 GB)
telemt_user_octets_to_client{user="hello"} 234873193432 (218.74 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 118
```