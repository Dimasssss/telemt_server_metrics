# Server Metrics 2026-03-11 13:50:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 84187.3 (23h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2001458
telemt_connections_bad_total 27779
telemt_handshake_timeouts_total 51445
telemt_upstream_connect_attempt_total 17532
telemt_upstream_connect_success_total 17523
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 982
telemt_me_reconnect_attempts_total 26101
telemt_me_reconnect_success_total 13269
telemt_me_reader_eof_total 14322
telemt_me_idle_close_by_peer_total 14322
telemt_me_route_drop_no_conn_total 736057
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1829548
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9638
telemt_desync_full_logged_total 2610
telemt_desync_suppressed_total 7028
telemt_desync_frames_bucket_total{bucket="1_2"} 2379
telemt_desync_frames_bucket_total{bucket="3_10"} 3724
telemt_desync_frames_bucket_total{bucket="gt_10"} 3535
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13809
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13263
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 1828059
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 24435858860 (22.76 GB)
telemt_user_octets_to_client{user="hello"} 520488949132 (484.74 GB)
telemt_user_unique_ips_current{user="hello"} 380
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84244.1 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 756243
telemt_connections_bad_total 13090
telemt_handshake_timeouts_total 51287
telemt_upstream_connect_attempt_total 27085
telemt_upstream_connect_success_total 24137
telemt_upstream_connect_fail_total 2948
telemt_upstream_connect_attempts_per_request{bucket="1"} 27085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2948
telemt_me_keepalive_timeout_total 2492
telemt_me_reconnect_attempts_total 17831
telemt_me_reconnect_success_total 16966
telemt_me_reader_eof_total 17933
telemt_me_idle_close_by_peer_total 17930
telemt_me_route_drop_no_conn_total 295391
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639026
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2783
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 1902
telemt_desync_frames_bucket_total{bucket="1_2"} 867
telemt_desync_frames_bucket_total{bucket="3_10"} 1013
telemt_desync_frames_bucket_total{bucket="gt_10"} 903
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17177
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16943
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 641513
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 6847260062 (6.38 GB)
telemt_user_octets_to_client{user="hello"} 181777273500 (169.29 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 84243.9 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1305707
telemt_connections_bad_total 8357
telemt_handshake_timeouts_total 119346
telemt_upstream_connect_attempt_total 22386
telemt_upstream_connect_success_total 22115
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 22386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 901
telemt_me_reconnect_attempts_total 32904
telemt_me_reconnect_success_total 16797
telemt_me_reader_eof_total 18064
telemt_me_idle_close_by_peer_total 18064
telemt_me_route_drop_no_conn_total 455059
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1129405
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2995
telemt_desync_full_logged_total 888
telemt_desync_suppressed_total 2107
telemt_desync_frames_bucket_total{bucket="1_2"} 725
telemt_desync_frames_bucket_total{bucket="3_10"} 1130
telemt_desync_frames_bucket_total{bucket="gt_10"} 1140
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17522
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16786
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 1129744
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 13302666061 (12.39 GB)
telemt_user_octets_to_client{user="hello"} 337618051401 (314.43 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 84244.5 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 938626
telemt_connections_bad_total 77222
telemt_handshake_timeouts_total 88748
telemt_upstream_connect_attempt_total 22910
telemt_upstream_connect_success_total 22910
telemt_upstream_connect_attempts_per_request{bucket="1"} 22910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 940
telemt_me_reconnect_attempts_total 19771
telemt_me_reconnect_success_total 18700
telemt_me_reader_eof_total 19825
telemt_me_idle_close_by_peer_total 19824
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 303190
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 747103
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1602
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 977
telemt_desync_frames_bucket_total{bucket="1_2"} 579
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18930
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18672
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 746463
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 8644753488 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 216672689372 (201.79 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84244.0 (23h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026544
telemt_connections_bad_total 6822
telemt_handshake_timeouts_total 9343
telemt_upstream_connect_attempt_total 22904
telemt_upstream_connect_success_total 22805
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 22904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10913
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 978
telemt_me_reconnect_attempts_total 22542
telemt_me_reconnect_success_total 18468
telemt_me_reader_eof_total 19489
telemt_me_idle_close_by_peer_total 19489
telemt_me_route_drop_no_conn_total 363430
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 932647
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3716
telemt_desync_full_logged_total 1370
telemt_desync_suppressed_total 2346
telemt_desync_frames_bucket_total{bucket="1_2"} 1304
telemt_desync_frames_bucket_total{bucket="3_10"} 1402
telemt_desync_frames_bucket_total{bucket="gt_10"} 1010
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18831
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18468
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 932388
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 13633565859 (12.70 GB)
telemt_user_octets_to_client{user="hello"} 331509132802 (308.74 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 146
```