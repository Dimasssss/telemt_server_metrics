# Server Metrics 2026-03-14 12:43:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 197085.2 (54h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5728139
telemt_connections_bad_total 64786
telemt_handshake_timeouts_total 126416
telemt_upstream_connect_attempt_total 41336
telemt_upstream_connect_success_total 41073
telemt_upstream_connect_fail_total 263
telemt_upstream_connect_attempts_per_request{bucket="1"} 41336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 263
telemt_me_keepalive_timeout_total 7866
telemt_me_reconnect_attempts_total 46509
telemt_me_reconnect_success_total 28948
telemt_me_reader_eof_total 31168
telemt_me_idle_close_by_peer_total 31167
telemt_me_route_drop_no_conn_total 2171088
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5251465
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20267
telemt_desync_full_logged_total 5551
telemt_desync_suppressed_total 14716
telemt_desync_frames_bucket_total{bucket="1_2"} 4887
telemt_desync_frames_bucket_total{bucket="3_10"} 7699
telemt_desync_frames_bucket_total{bucket="gt_10"} 7681
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 29917
telemt_me_refill_failed_total 543
telemt_me_writer_restored_same_endpoint_total 28935
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 969
telemt_user_connections_total{user="hello"} 5253034
telemt_user_connections_current{user="hello"} 1771
telemt_user_octets_from_client{user="hello"} 81971949284 (76.34 GB)
telemt_user_octets_to_client{user="hello"} 1672176006161 (1.52 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 96749.0 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1116236
telemt_connections_bad_total 58965
telemt_handshake_timeouts_total 26217
telemt_upstream_connect_attempt_total 24694
telemt_upstream_connect_success_total 24387
telemt_upstream_connect_fail_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 24694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 307
telemt_me_keepalive_timeout_total 2426
telemt_me_reconnect_attempts_total 37941
telemt_me_reconnect_success_total 17531
telemt_me_reader_eof_total 19061
telemt_me_idle_close_by_peer_total 19060
telemt_me_route_drop_no_conn_total 378128
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 921118
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2567
telemt_desync_full_logged_total 807
telemt_desync_suppressed_total 1760
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 1068
telemt_desync_frames_bucket_total{bucket="gt_10"} 830
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18417
telemt_me_refill_failed_total 631
telemt_me_writer_restored_same_endpoint_total 17523
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 886
telemt_user_connections_total{user="hello"} 923032
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 10183768925 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 328238757836 (305.70 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 226705.7 (62h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4061446
telemt_connections_bad_total 46569
telemt_handshake_timeouts_total 281383
telemt_upstream_connect_attempt_total 50984
telemt_upstream_connect_success_total 50962
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 50984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 11285
telemt_me_reconnect_attempts_total 45368
telemt_me_reconnect_success_total 39361
telemt_me_reader_eof_total 41804
telemt_me_idle_close_by_peer_total 41802
telemt_me_route_drop_no_conn_total 1395802
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3396548
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10854
telemt_desync_full_logged_total 3666
telemt_desync_suppressed_total 7188
telemt_desync_frames_bucket_total{bucket="1_2"} 1994
telemt_desync_frames_bucket_total{bucket="3_10"} 3910
telemt_desync_frames_bucket_total{bucket="gt_10"} 4950
telemt_pool_swap_total 209
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 39946
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 39320
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 3395686
telemt_user_connections_current{user="hello"} 925
telemt_user_octets_from_client{user="hello"} 57976820328 (54.00 GB)
telemt_user_octets_to_client{user="hello"} 1211457744837 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 226708.2 (62h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2648276
telemt_connections_bad_total 23515
telemt_handshake_timeouts_total 343785
telemt_upstream_connect_attempt_total 69792
telemt_upstream_connect_success_total 67283
telemt_upstream_connect_fail_total 2372
telemt_upstream_connect_attempts_per_request{bucket="1"} 69518
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27091
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2371
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 21009
telemt_me_reconnect_attempts_total 61766
telemt_me_reconnect_success_total 48982
telemt_me_reader_eof_total 52472
telemt_me_idle_close_by_peer_total 52464
telemt_me_route_drop_no_conn_total 878622
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2068752
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4117
telemt_desync_full_logged_total 1355
telemt_desync_suppressed_total 2762
telemt_desync_frames_bucket_total{bucket="1_2"} 1171
telemt_desync_frames_bucket_total{bucket="3_10"} 1683
telemt_desync_frames_bucket_total{bucket="gt_10"} 1263
telemt_pool_swap_total 194
telemt_me_writer_removed_unexpected_total 49808
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 48957
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 826
telemt_user_connections_total{user="hello"} 2075260
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 30667032283 (28.56 GB)
telemt_user_octets_to_client{user="hello"} 737488434398 (686.84 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 96141.8 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1104432
telemt_connections_bad_total 18174
telemt_handshake_timeouts_total 14171
telemt_upstream_connect_attempt_total 23031
telemt_upstream_connect_success_total 22378
telemt_upstream_connect_fail_total 653
telemt_upstream_connect_attempts_per_request{bucket="1"} 23031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 653
telemt_me_keepalive_timeout_total 1819
telemt_me_reconnect_attempts_total 86761
telemt_me_reconnect_success_total 17595
telemt_me_reader_eof_total 20164
telemt_me_idle_close_by_peer_total 20163
telemt_me_route_drop_no_conn_total 445608
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1023294
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2725
telemt_desync_full_logged_total 855
telemt_desync_suppressed_total 1870
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 953
telemt_desync_frames_bucket_total{bucket="gt_10"} 783
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 19915
telemt_me_refill_failed_total 2156
telemt_me_writer_restored_same_endpoint_total 17590
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 2320
telemt_user_connections_total{user="hello"} 1022496
telemt_user_connections_current{user="hello"} 695
telemt_user_octets_from_client{user="hello"} 17829369648 (16.60 GB)
telemt_user_octets_to_client{user="hello"} 344726562512 (321.05 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 89
```