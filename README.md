# Server Metrics 2026-03-15 14:40:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 59170.7 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1843604
telemt_connections_bad_total 100782
telemt_handshake_timeouts_total 20752
telemt_upstream_connect_attempt_total 11775
telemt_upstream_connect_success_total 11726
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5550
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13652
telemt_me_reconnect_success_total 8761
telemt_me_reader_eof_total 9380
telemt_me_idle_close_by_peer_total 9380
telemt_me_route_drop_no_conn_total 631721
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1560650
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5909
telemt_desync_full_logged_total 1646
telemt_desync_suppressed_total 4263
telemt_desync_frames_bucket_total{bucket="1_2"} 1486
telemt_desync_frames_bucket_total{bucket="3_10"} 2276
telemt_desync_frames_bucket_total{bucket="gt_10"} 2147
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 9056
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8750
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 1560248
telemt_user_connections_current{user="hello"} 2351
telemt_user_octets_from_client{user="hello"} 22259093224 (20.73 GB)
telemt_user_octets_to_client{user="hello"} 611650673020 (569.64 GB)
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 59171.2 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 747446
telemt_connections_bad_total 40321
telemt_handshake_timeouts_total 58146
telemt_upstream_connect_attempt_total 14984
telemt_upstream_connect_success_total 14911
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 14984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11701
telemt_me_reconnect_success_total 11606
telemt_me_reader_eof_total 12271
telemt_me_idle_close_by_peer_total 12271
telemt_me_route_drop_no_conn_total 186343
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563458
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1992
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1304
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 524
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 11752
telemt_me_writer_restored_same_endpoint_total 11594
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 563709
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 7857668487 (7.32 GB)
telemt_user_octets_to_client{user="hello"} 212196570192 (197.62 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 59171.1 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1608613
telemt_connections_bad_total 46464
telemt_handshake_timeouts_total 165234
telemt_upstream_connect_attempt_total 12993
telemt_upstream_connect_success_total 12932
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 12993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11203
telemt_me_reconnect_success_total 9949
telemt_me_reader_eof_total 10543
telemt_me_idle_close_by_peer_total 10543
telemt_me_route_drop_no_conn_total 437698
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 995075
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2492
telemt_desync_full_logged_total 920
telemt_desync_suppressed_total 1572
telemt_desync_frames_bucket_total{bucket="1_2"} 573
telemt_desync_frames_bucket_total{bucket="3_10"} 959
telemt_desync_frames_bucket_total{bucket="gt_10"} 960
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10122
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9930
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 991159
telemt_user_connections_current{user="hello"} 1295
telemt_user_octets_from_client{user="hello"} 14447802248 (13.46 GB)
telemt_user_octets_to_client{user="hello"} 357181308504 (332.65 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 59171.1 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777928
telemt_connections_bad_total 72948
telemt_handshake_timeouts_total 40574
telemt_upstream_connect_attempt_total 159995
telemt_upstream_connect_success_total 159505
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 159993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52229
telemt_me_reconnect_success_total 11796
telemt_me_reader_eof_total 13390
telemt_me_idle_close_by_peer_total 13390
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 171339
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448648
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1175
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 876
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13171
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 11764
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1375
telemt_user_connections_total{user="hello"} 593263
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 11152188021 (10.39 GB)
telemt_user_octets_to_client{user="hello"} 200454140849 (186.69 GB)
telemt_user_msgs_from_client{user="hello"} 2851432
telemt_user_msgs_to_client{user="hello"} 10455130
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 59172.0 (16h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 792616
telemt_connections_bad_total 9355
telemt_handshake_timeouts_total 16608
telemt_upstream_connect_attempt_total 13061
telemt_upstream_connect_success_total 12990
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13704
telemt_me_reconnect_success_total 10024
telemt_me_reader_eof_total 10713
telemt_me_idle_close_by_peer_total 10713
telemt_me_route_drop_no_conn_total 197293
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646462
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2318
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1537
telemt_desync_frames_bucket_total{bucket="1_2"} 698
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 725
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10257
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10016
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 646506
telemt_user_connections_current{user="hello"} 891
telemt_user_octets_from_client{user="hello"} 8164848584 (7.60 GB)
telemt_user_octets_to_client{user="hello"} 241464375268 (224.88 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 123
```