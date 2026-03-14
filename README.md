# Server Metrics 2026-03-14 06:29:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 174668.4 (48h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4918425
telemt_connections_bad_total 40035
telemt_handshake_timeouts_total 112782
telemt_upstream_connect_attempt_total 36679
telemt_upstream_connect_success_total 36440
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 36679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 7324
telemt_me_reconnect_attempts_total 35566
telemt_me_reconnect_success_total 25417
telemt_me_reader_eof_total 27277
telemt_me_idle_close_by_peer_total 27276
telemt_me_route_drop_no_conn_total 1863048
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4514279
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17344
telemt_desync_full_logged_total 4690
telemt_desync_suppressed_total 12654
telemt_desync_frames_bucket_total{bucket="1_2"} 4327
telemt_desync_frames_bucket_total{bucket="3_10"} 6615
telemt_desync_frames_bucket_total{bucket="gt_10"} 6402
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 26099
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25404
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 682
telemt_user_connections_total{user="hello"} 4515787
telemt_user_connections_current{user="hello"} 1148
telemt_user_octets_from_client{user="hello"} 65928137952 (61.40 GB)
telemt_user_octets_to_client{user="hello"} 1423771155145 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 74342.4 (20h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809264
telemt_connections_bad_total 53807
telemt_handshake_timeouts_total 14819
telemt_upstream_connect_attempt_total 20201
telemt_upstream_connect_success_total 19930
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 20201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 2141
telemt_me_reconnect_attempts_total 17662
telemt_me_reconnect_success_total 14198
telemt_me_reader_eof_total 15089
telemt_me_idle_close_by_peer_total 15088
telemt_me_route_drop_no_conn_total 265100
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642138
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1873
telemt_desync_full_logged_total 566
telemt_desync_suppressed_total 1307
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 845
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14509
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 14190
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 644054
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 6760436213 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 215687574196 (200.87 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 204289.0 (56h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3531261
telemt_connections_bad_total 38567
telemt_handshake_timeouts_total 232355
telemt_upstream_connect_attempt_total 46169
telemt_upstream_connect_success_total 46148
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 46169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10662
telemt_me_reconnect_attempts_total 40668
telemt_me_reconnect_success_total 35694
telemt_me_reader_eof_total 37915
telemt_me_idle_close_by_peer_total 37914
telemt_me_route_drop_no_conn_total 1208702
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2946103
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9712
telemt_desync_full_logged_total 3260
telemt_desync_suppressed_total 6452
telemt_desync_frames_bucket_total{bucket="1_2"} 1692
telemt_desync_frames_bucket_total{bucket="3_10"} 3506
telemt_desync_frames_bucket_total{bucket="gt_10"} 4514
telemt_pool_swap_total 193
telemt_me_writer_removed_unexpected_total 36190
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35653
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 2945257
telemt_user_connections_current{user="hello"} 648
telemt_user_octets_from_client{user="hello"} 48776811152 (45.43 GB)
telemt_user_octets_to_client{user="hello"} 1053531971469 (981.18 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 204291.6 (56h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2360016
telemt_connections_bad_total 23199
telemt_handshake_timeouts_total 277571
telemt_upstream_connect_attempt_total 63660
telemt_upstream_connect_success_total 61172
telemt_upstream_connect_fail_total 2351
telemt_upstream_connect_attempts_per_request{bucket="1"} 63386
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2350
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20510
telemt_me_reconnect_attempts_total 53053
telemt_me_reconnect_success_total 44007
telemt_me_reader_eof_total 47184
telemt_me_idle_close_by_peer_total 47177
telemt_me_route_drop_no_conn_total 796158
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1863017
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3897
telemt_desync_full_logged_total 1262
telemt_desync_suppressed_total 2635
telemt_desync_frames_bucket_total{bucket="1_2"} 1054
telemt_desync_frames_bucket_total{bucket="3_10"} 1617
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 181
telemt_me_writer_removed_unexpected_total 44672
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43983
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 1869054
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 28212882807 (26.28 GB)
telemt_user_octets_to_client{user="hello"} 688278353122 (641.01 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 73725.2 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783103
telemt_connections_bad_total 8100
telemt_handshake_timeouts_total 9188
telemt_upstream_connect_attempt_total 18780
telemt_upstream_connect_success_total 18277
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 18780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_timeout_total 1571
telemt_me_reconnect_attempts_total 59921
telemt_me_reconnect_success_total 14616
telemt_me_reader_eof_total 16387
telemt_me_idle_close_by_peer_total 16386
telemt_me_route_drop_no_conn_total 301556
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731406
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1773
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 16157
telemt_me_refill_failed_total 1411
telemt_me_writer_restored_same_endpoint_total 14611
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1541
telemt_user_connections_total{user="hello"} 731266
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 12983378456 (12.09 GB)
telemt_user_octets_to_client{user="hello"} 245978734736 (229.09 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 82
```