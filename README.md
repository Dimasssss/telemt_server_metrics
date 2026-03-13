# Server Metrics 2026-03-13 09:07:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 97724.0 (27h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2769233
telemt_connections_bad_total 36383
telemt_handshake_timeouts_total 37925
telemt_upstream_connect_attempt_total 19190
telemt_upstream_connect_success_total 19085
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 19190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 1392
telemt_me_reconnect_attempts_total 24292
telemt_me_reconnect_success_total 14232
telemt_me_reader_eof_total 15338
telemt_me_idle_close_by_peer_total 15337
telemt_me_route_drop_no_conn_total 1028799
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2531018
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11235
telemt_desync_full_logged_total 2904
telemt_desync_suppressed_total 8331
telemt_desync_frames_bucket_total{bucket="1_2"} 2885
telemt_desync_frames_bucket_total{bucket="3_10"} 4206
telemt_desync_frames_bucket_total{bucket="gt_10"} 4144
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14742
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14219
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 2530584
telemt_user_connections_current{user="hello"} 1816
telemt_user_octets_from_client{user="hello"} 35467772868 (33.03 GB)
telemt_user_octets_to_client{user="hello"} 831288707612 (774.20 GB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 127344.5 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1133487
telemt_connections_bad_total 14178
telemt_handshake_timeouts_total 102540
telemt_upstream_connect_attempt_total 31664
telemt_upstream_connect_success_total 31633
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23787
telemt_me_reconnect_success_total 23662
telemt_me_reader_eof_total 25223
telemt_me_idle_close_by_peer_total 25223
telemt_me_route_drop_no_conn_total 347134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975468
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4331
telemt_desync_full_logged_total 1315
telemt_desync_suppressed_total 3016
telemt_desync_frames_bucket_total{bucket="1_2"} 1581
telemt_desync_frames_bucket_total{bucket="3_10"} 1425
telemt_desync_frames_bucket_total{bucket="gt_10"} 1325
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 23894
telemt_me_writer_restored_same_endpoint_total 23653
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 977396
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 14908121808 (13.88 GB)
telemt_user_octets_to_client{user="hello"} 359606111747 (334.91 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 127344.2 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2184788
telemt_connections_bad_total 24589
telemt_handshake_timeouts_total 145340
telemt_upstream_connect_attempt_total 29233
telemt_upstream_connect_success_total 29223
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13810
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1806
telemt_me_reconnect_attempts_total 23819
telemt_me_reconnect_success_total 22535
telemt_me_reader_eof_total 23873
telemt_me_idle_close_by_peer_total 23872
telemt_me_route_drop_no_conn_total 709891
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1744697
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5826
telemt_desync_full_logged_total 1853
telemt_desync_suppressed_total 3973
telemt_desync_frames_bucket_total{bucket="1_2"} 949
telemt_desync_frames_bucket_total{bucket="3_10"} 2128
telemt_desync_frames_bucket_total{bucket="gt_10"} 2749
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22758
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22494
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 1744132
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 30554950676 (28.46 GB)
telemt_user_octets_to_client{user="hello"} 631853294697 (588.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 127344.8 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1386485
telemt_connections_bad_total 14224
telemt_handshake_timeouts_total 85016
telemt_upstream_connect_attempt_total 42204
telemt_upstream_connect_success_total 39900
telemt_upstream_connect_fail_total 2167
telemt_upstream_connect_attempts_per_request{bucket="1"} 41930
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2166
telemt_me_keepalive_timeout_total 11462
telemt_me_reconnect_attempts_total 36647
telemt_me_reconnect_success_total 27706
telemt_me_reader_eof_total 29836
telemt_me_idle_close_by_peer_total 29829
telemt_me_route_drop_no_conn_total 487377
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1155295
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2200
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1480
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 848
telemt_desync_frames_bucket_total{bucket="gt_10"} 748
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 28182
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27682
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 1160058
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 17456187573 (16.26 GB)
telemt_user_octets_to_client{user="hello"} 460635723286 (429.00 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 127344.4 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1539127
telemt_connections_bad_total 33553
telemt_handshake_timeouts_total 12648
telemt_upstream_connect_attempt_total 40627
telemt_upstream_connect_success_total 40139
telemt_upstream_connect_fail_total 488
telemt_upstream_connect_attempts_per_request{bucket="1"} 40627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 488
telemt_me_keepalive_timeout_total 2197
telemt_me_reconnect_attempts_total 47871
telemt_me_reconnect_success_total 33801
telemt_me_reader_eof_total 35430
telemt_me_idle_close_by_peer_total 35430
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 563103
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1406898
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4907
telemt_desync_full_logged_total 1755
telemt_desync_suppressed_total 3152
telemt_desync_frames_bucket_total{bucket="1_2"} 1500
telemt_desync_frames_bucket_total{bucket="3_10"} 1584
telemt_desync_frames_bucket_total{bucket="gt_10"} 1823
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 34614
telemt_me_refill_failed_total 435
telemt_me_writer_restored_same_endpoint_total 33740
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 813
telemt_user_connections_total{user="hello"} 1406701
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 18160036196 (16.91 GB)
telemt_user_octets_to_client{user="hello"} 487930365380 (454.42 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 132
```